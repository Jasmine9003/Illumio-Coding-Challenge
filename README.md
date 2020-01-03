# Illumio-Coding-Challenge

This is repository contains solution of Illumio coding challenge.

### Testing
I used JUnit for testing the required functionality. I tried testing by covering the corner cases of ports and IP address. The main thing that I wanted to test was to make sure that the program worked for the case when there was a range in the port and also the ipAddress.

### Implementation
For this assignment, I decided to have an efficient run time.I did it by creating a HashSet of NetworkRule object. I overrode the equals methods such that 2 network rules are similar when direction, protocol, port and IP address are same. This leads to O(1) run time. We can incorporate some design patterns for the solution, proxy pattern would work in this scenario. 

### Modifications
I took the entire time given to me to find an efficient solution as submitted but if I had more time, I would have added validations to all the input fields. I would have declared enums for all defined protocols likd TCP, UDP.

### Teams
I would like to join Policy team.
