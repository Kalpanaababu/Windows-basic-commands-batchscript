

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

<img width="632" height="107" alt="image" src="https://github.com/user-attachments/assets/865f1329-2df1-4487-ba7e-e2ba470da0fe" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="944" height="106" alt="image" src="https://github.com/user-attachments/assets/59a5b8f1-03d7-4ef6-abb0-9d8ff130a51e" />

## COMMAND AND OUTPUT
Create the file Rose.txt

<img width="751" height="421" alt="image" src="https://github.com/user-attachments/assets/6717d34c-cc3a-4326-896f-d83652c03abd" />



## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="851" height="124" alt="image" src="https://github.com/user-attachments/assets/06d8b32a-f9b4-4387-b341-c3d79590c673" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="838" height="148" alt="image" src="https://github.com/user-attachments/assets/c0e0451f-274b-4473-9b2b-4f51aba14db5" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="593" height="212" alt="image" src="https://github.com/user-attachments/assets/a3565d26-a75c-4c1f-b59e-33695bf4e8aa" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="750" height="815" alt="Screenshot 2025-11-10 054328" src="https://github.com/user-attachments/assets/c6fbddf7-0826-40eb-9e3d-26ac4ae4cb9d" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="764" height="240" alt="Screenshot 2025-11-10 054339" src="https://github.com/user-attachments/assets/018678b5-9864-455c-bd15-3e151314ab45" />



## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="673" height="234" alt="image" src="https://github.com/user-attachments/assets/ea898c90-acc0-4513-b07d-d10da0871979" />



## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


## OUTPUT

<img width="668" height="155" alt="Screenshot 2025-11-10 054346" src="https://github.com/user-attachments/assets/15593839-c7cb-440e-b23a-458995379c8c" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT



<img width="757" height="313" alt="Screenshot 2025-11-10 054352" src="https://github.com/user-attachments/assets/8789fd5f-f568-4184-ae30-27fd18c7a52a" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="592" height="270" alt="Screenshot 2025-11-10 054359" src="https://github.com/user-attachments/assets/db361e18-7e29-4a7a-b4e2-b3a97d891ab4" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="1003" height="303" alt="Screenshot 2025-11-10 054405" src="https://github.com/user-attachments/assets/be6fd78d-7bd6-4075-8a63-6234cc583c63" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="647" height="592" alt="Screenshot 2025-11-10 054412" src="https://github.com/user-attachments/assets/05c34974-cc7f-4665-9a7a-8028beeb6627" />


# RESULT:
The commands/batch files are executed successfully.

