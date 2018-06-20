---
triggers:
    hard:
        condition:
            sl.ec == true
actions:
    "ec2":
        operations: 
            - sl.ec2 = true
---

ec
