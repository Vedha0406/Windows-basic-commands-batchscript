# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/30bb0cd7-6636-4e68-91f0-c3198adde035)

Remove the directory "my-folder"

## COMMAND AND OUTPUT

![image](https://github.com/user-attachments/assets/7e096df8-76af-4c77-981b-8b81507c8cb7)

Create the file Rose.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/b46e7404-0dd1-47a5-9a57-4a9888719849)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/08a50af4-c90a-44c1-9758-d23c453a9f70)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/73066293-979c-4502-a1e2-e43506b60489)

Remove the file hello1.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/db521757-b3e4-4a67-aebe-b4f39a88c74a)

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/98a2ad19-2e1d-47dd-8456-038f629231ee)

List out all the associated file extensions 

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/2eaeb9e4-d232-4390-9f25-7966c3667cca)

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![image](https://github.com/user-attachments/assets/56b40fb7-a6b2-435a-89db-150ff71ffec3)

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
![image](https://github.com/user-attachments/assets/fd262c71-7b59-47a4-aac3-622e4a1ca3ee)



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![image](https://github.com/user-attachments/assets/ef1b0531-3043-4a73-ad27-d0d9cf6c974a)




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


![image](https://github.com/user-attachments/assets/3d6d01d5-04c8-4b09-9c0b-9a5847d44326)


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![image](https://github.com/user-attachments/assets/1b3a5e7d-2985-4f68-96f9-2600c7c4efe2)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![image](https://github.com/user-attachments/assets/2aacc517-ed14-4002-a9d0-77e0607f82cd)



# RESULT:
The commands/batch files are executed successfully.

