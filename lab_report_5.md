# CSE 15L Lab Report 4
## Kavon Naziri - A17499205

1. Student Edstem Post - Lab 7 ListExamples.java failure
![Image](cse15l_lab5_ss3.png)
![Image](cse15l_lab5_ss4.png)

For lab7 whenever I run my tests for the merge method in ListExamples.java using the bash script test.sh, both of my tests fail with this failure message. I also attached my code for my merge method and was hoping someone could help me figure out this bug. 

2. TA response
Take a closer look at your failure messages, do you see anything that could help you figure out what is going on. Is this a bug or a failure in your code. Try using the jdb command (java debugger) to assess the different values in your code as you run it. Don't forget to add the -g option when you compile so that you can have access to the local variables. Also don't forget to use -classpath instead of -cp when running the command.

3. Student Bug Diagnosis


