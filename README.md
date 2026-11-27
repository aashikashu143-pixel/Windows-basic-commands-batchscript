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

Remove the directory "my-folder"

<img width="961" height="187" alt="image" src="https://github.com/user-attachments/assets/975e0a91-221c-454b-badd-364104f5a118" />


## COMMAND AND OUTPUT

<img width="930" height="250" alt="image" src="https://github.com/user-attachments/assets/969ea16e-dd12-4ab4-8613-fbfd827b8bc9" />


Create the file Rose.txt

<img width="858" height="217" alt="image" src="https://github.com/user-attachments/assets/4fba3706-19d1-43fc-9779-293bf5932cc7" />


## COMMAND AND OUTPUT


<img width="858" height="217" alt="image" src="https://github.com/user-attachments/assets/251a8945-37a4-4bed-a062-182efd46e3e1" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="1055" height="111" alt="image" src="https://github.com/user-attachments/assets/7ddebf54-a468-47a9-8c6b-f4f013a8b164" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT


<img width="1055" height="111" alt="image" src="https://github.com/user-attachments/assets/f205be2b-e696-46d6-94cf-342275083fbf" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="638" height="867" alt="image" src="https://github.com/user-attachments/assets/37a81d6d-46de-4411-9d9a-307e0226b271" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="872" height="200" alt="image" src="https://github.com/user-attachments/assets/a615eaa2-aa65-4794-81e4-5d14e27631fd" />


List out all the associated file extensions 

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="882" height="106" alt="image" src="https://github.com/user-attachments/assets/6891a361-4a14-4d61-9fdf-8b491378937c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="888" height="267" alt="image" src="https://github.com/user-attachments/assets/b52572cb-3c7b-4437-8aab-83529311b023" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="883" height="201" alt="image" src="https://github.com/user-attachments/assets/ef77477b-5563-4881-9c30-6dd153010af6" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="853" height="89" alt="image" src="https://github.com/user-attachments/assets/429c3a3c-d9fc-4812-8025-12fec247128b" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="829" height="404" alt="image" src="https://github.com/user-attachments/assets/21fd9632-9905-43af-8e1a-6f6e52225b75" />


# RESULT:
The commands/batch files are executed successfully.

