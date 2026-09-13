male(othman).
male(khalid).
male(yzeed).

female(hessah).
female(nouf).
female(aljawhara).
female(sara).

parent(othman, nouf).
parent(hessah, nouf).

parent(khalid, aljawhara).
parent(nouf, aljawhara).

parent(khalid, sara).
parent(nouf, sara).

parent(khalid, yzeed).
parent(nouf, yzeed).

father(X, Y) :-
    male(X),
    parent(X, Y).

mother(X, Y) :-
    female(X),
    parent(X, Y).

sister(X, Y) :-
    female(X),
    parent(P, X),
    parent(P, Y),
    X \= Y.

brother(X, Y) :-
    male(X),
    parent(P, X),
    parent(P, Y),
    X \= Y.
