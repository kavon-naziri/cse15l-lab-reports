# CSE 15L Lab Report 2
## Kavon Naziri - A17499205

### Part 1

Code:

![Image](cse15l_lab2_ss1-3.png)
![Image](cse15l_lab2_ss1-4.png)

Screenshot 1:
![Image](cse15l_lab2_ss1-1.png)

- In this first screenshot the method handleRequest(URI url) within the Handler class is called
- The entire url passes as an argument to the method handleRequest(URI url). The method url.getPath() returns the path "/add-message" making the first if statement in the handlRequest method true. The method url.getQuery returns the query "s=Hello" which is then split into the string array called parameters as follows: ["s", "Hello']. Because the element at index 0 of parameters is in fact "s", the second if statement returns true and the instance variable numMessages increments by one and the formatted string including the bullet point number, the message (parameters[1]), and a line break is concatanated to the String called message which is then returned.
- The instance variable numMessages increments from 0 to 1 and the the instance variable messages becomes "1. Hello\n"

Screenshot 2:
![Image](cse15l_lab2_ss1-2.png)
- In this second screenshot the method handleRequest(URI url) within the Handler class is called
- The entire url again passes as an argument to the method handleRequest(URI url). The method url.getPath() returns the path "/add-message" making the first if statement in the handlRequest method true. The method url.getQuery returns the query "s=How are you" which is then split into the string array called parameters as follows: ["s", "How are you"]. Because the element at index 0 of parameters is in fact "s", the second if statement returns true and the instance variable numMessages increments by one and the formatted string including the bullet point number, the message (parameters[1]), and a line break is concatanated to the String called message which is then returned.
- The instance variable numMessages increments from 1 to 2 and the the instance variable messages becomes "1. Hello\n2. How+are+you\n"

### Part 2

Path to private key for my SSH key for loggin into ieng6 on my machine:
![Image](cse15l_lab2_ss2-1.png)

Path to public key for my SSH key for logging into ieng6 on ieng6-202:
![Image](cse15l_lab2_ss2-2.png)

Logging into ieng6 without being asked for a passowrd:
![Image](cse15l_lab2_ss2-3.png)

### Part 3

Something I learned in the week 3 lab which I did not know before was the use of the scp and mkdir terminal commands. The mkdir command is used to make directories. In the week 3 lab, mkdir was used to make a .ssh directory where my SSH key could be stored. scp, meaning "secure copy" allows for the secure transfer of files or directories between two locations. In the week 3 lab, the scp command was used to securely transfer my public SSH key to the ieng6 machine. 
