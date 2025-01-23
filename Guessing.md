```mermaid
flowchart TD;
    Start([Start])--> End([End])
'''
title: Number Guessing Game
flowchart LR
    A[Start Game] --> B[Set Range is 1-100];
    B--> C[Prompt User to Guess Number];
    C--> D[Set Out Answer Box];
    D--> E[If Vaild: Compare Guess With Random Number];
    E--> F[If Invaild Display Error: Enter Valid Number];

