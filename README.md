# lambda-persistency-poc
See [Twistlock Labs](https://www.twistlock.com/labs-blog/gaining-persistency-vulnerable-lambdas/) for more info.
 
A repository containing two PoCs of an attacker gaining persistency on a vulnerable AWS python Lambda.
 
Both PoCs compromise a Lambda instance by replacing the bootstrap process (the Lambda runtime) with a malicious version.
 
 
- **poc** - a PoC relying on an RCE primitive that executes code in the context of the vulnerable function
- **exteranl_process_poc** - a PoC relying on an RCE primitive that executes code in a child proccess of the vulnerable function
