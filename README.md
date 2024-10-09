The dataset contains detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal or a "Neptune" attack, providing a foundation for binomial classification.

A Neptune attack, also known as a SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests, causing the system to become unresponsive to legitimate traffic. It exploits the TCP handshake process to consume resources on the target machine.

The training set contains 86,845 rows, including whether the activity (column - Attack) is normal or not. Using this I train a Machine Learning model, then predicted whether the 21,712 entries in the test set have a normal activity or not (Neptune).

Note: 

In the target variable (Attack), “normal” means normal activity (no attack) i.e., attack = 0

“neptune” means Neptune attack. i.e., attack = 1
