## Lab Report 4 

# Step 4: Log in to ieng6

I pressed `<up>` to access the command `ssh ieng6wi23asl@ieng6.ucsd.edu` from my history. Luckily, I configured the key to log in from my laptop without a password so I do not have to enter my password.

![image](https://user-images.githubusercontent.com/122569112/221385222-36ef03de-562c-4e4f-93a3-fb1ff9ea1917.png)

# Step 5: Clone your fork of the repository from your github account

For this step, I had to press `<up>` 12 times in order to access the command `git clone git@github.com:kabirvats/lab7.git`. I used this version of the cloned url in order to directly push and commit from the comamand line.

![image](https://user-images.githubusercontent.com/122569112/221385306-645b716e-4426-4e99-b3ec-d305c5b7c2f5.png)

# Step 6: Run the tests, demonstrating that they fail

To do this step, I first manually typed `cd lab7` to enter the cloned directory. Then, I pressed `<up>` 9 times to access the command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`. Following this, I pressed `<up>` 9 times again to access the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`.

The result was this:

![image](https://user-images.githubusercontent.com/122569112/221385474-4a7235c7-7de2-434a-855e-11746b8e796d.png)

# Step 7: Edit the code to fix the failing test

I had to press `<up>` 12 times to access the command `nano ListExamples.java`. Following this, I navigated down to the merge method and changed the line in the third while loop from `index1 += 1` to `index2 += 1`, so the file appeared like this:

![image](https://user-images.githubusercontent.com/122569112/221385590-6b65ad19-5bd9-425c-97b3-9990ebd7a0aa.png)

I then pressed `<ctrl + X> <y> <Enter>` to save the changes.

# Step 8: Run the tests, demonstrating that they now succeed

I pressed `<up>` 3 times to access the compile command `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java`, then I pressed up 3 times to run the tests with the command `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests`. The tests now succeeded.

![image](https://user-images.githubusercontent.com/122569112/221385722-2b00af7a-ee0d-4003-96e5-f20b60b1f57c.png)

# Step 9: Commit and push the resulting change to your github account

I pressed `<up>` 12 times to use `git add ListExamples.java`, then I pressed `<up>` 12 times to access and run the command `git commit -m "Fixed Infinite Loop"`, and I manually typed the command `git push`, pushing the changes to my GitHub account on the internet.

![image](https://user-images.githubusercontent.com/122569112/221385825-947dd3fb-8c0d-41d8-951d-79042fa7ef52.png)

The changes were then reflected on the internet version of the repository as well.

