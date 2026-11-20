# Exploring Your System's Security

## Task 1 --- List System Users

Run:

    cat /etc/passwd

### Screenshot

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4a9693d5-e3c0-4dda-873b-67a2f3d150f6" />



### Questions

1.  How many users exist on the system?
Ans. 37 users on this system.
3.  Which accounts appear to be system accounts?
Ans.  Binary_Buddies and Script_sprinters
5.  Why do operating systems create system accounts?
Ans.  Operating systems create system accounts to give internal processes, background services, and daemons a secure identity so they can run and access resources without requiring human logins.

### Reflection

Explain why understanding system users is important for cybersecurity.
Ans. Understanding system users is important for cyber security because it helps us know who can access a computer system and what they are allowed to do. 
Moreover, we can prevent unauthorised access, protect sensitive information, identify suspicious activities, and reduce security risks. It also helps administrators give users only the access they need.
------------------------------------------------------------------------

## Task 2 --- Inspect Running Processes

Run:

    ps aux

### Screen shot
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ef4f5c29-7883-4fa9-8cd3-1c268b7e159a" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/c9ffc38d-9aa3-4de7-8bf2-081451de9884" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/cc099d04-3177-48ca-8402-dba681342f79" />
<img width="850" height="333" alt="image" src="https://github.com/user-attachments/assets/1dfa22ce-ac97-444a-a052-7a16d07ad832" />




### Questions

1.  Which processes are running as `root`?
2.  <img width="812" height="927" alt="image" src="https://github.com/user-attachments/assets/68b54b1d-7421-4532-84d4-a9aec87825b1" />

3.  Why can processes running as root be dangerous?
4.  What could happen if a malicious program ran with root privileges?

### Reflection

What did you learn about system processes and security?

------------------------------------------------------------------------

## Task 3 --- Identify Open Network Ports

Run:

    ss -tuln

### Screenshot

(Add screenshot here)

### Questions

1.  Which ports are open?
2.  Which services appear to be listening?
3.  Why might open ports represent a security risk?

### Reflection

Explain the relationship between open ports and potential attack
surfaces.
