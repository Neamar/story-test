---
triggers:
    hard:
        condition:
            global.current_turn == 1
actions:
    "e1":
        operations: 
            - sl.e1 = true
    "e2":
        operations: 
            - sl.e2 = true
---

e
