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
<img width="961" height="187" alt="514892979-6a329478-42d9-4f49-8896-944b4d12aace" src="https://github.com/user-attachments/assets/92d84061-6cd6-47a8-9686-c0b198666399" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="930" height="250" alt="514893005-f3178dfc-898c-4fab-9b52-d5454b0b226a" src="https://github.com/user-attachments/assets/691c756f-e12b-4edb-81f7-570ca9287f12" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="858" height="217" alt="514893030-2fa5bb09-4d9d-47e1-8753-72368a5baae7" src="https://github.com/user-attachments/assets/9e41810f-ec9a-41aa-bcd7-48e4a5028f38" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="1055" height="111" alt="514893070-84f0a91c-b098-4b14-bdc5-8fcce2602361" src="https://github.com/user-attachments/assets/9b6547b5-ed8d-432e-ac93-3bff8c935108" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="992" height="139" alt="514893097-c6105b44-5b1c-4532-be6b-f86359b1d5bd" src="https://github.com/user-attachments/assets/9a96b2ef-b400-4133-b272-4f9cd10d05c4" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="1055" height="111" alt="514893070-84f0a91c-b098-4b14-bdc5-8fcce2602361" src="https://github.com/user-attachments/assets/94b80332-e1bd-4e12-b13b-bc2aab64b4e8" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="876" height="236" alt="514893120-24480c34-9f7e-4c78-9387-667db6bc4130" src="https://github.com/user-attachments/assets/5ccafe25-4bb9-4442-a310-01e7cb51d76e" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="638" height="867" alt="514893147-f4b5e375-69d7-4200-9c8c-7dd48f64ddde" src="https://github.com/user-attachments/assets/ae28dd6d-b491-488c-afd8-b5029d31a20e" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="872" height="200" alt="514893210-9c570964-1462-4375-8cfa-509dc874d848" src="https://github.com/user-attachments/assets/d59af770-e2c4-4192-b3c0-8fbbf791f6fd" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="882" height="106" alt="514893233-8e0191de-dba9-498e-8f27-e6f2d7ce677e" src="https://github.com/user-attachments/assets/addffa64-b1a6-4b6a-81ce-705d4842bc1c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="888" height="267" alt="514893356-f85fe6e3-0071-42cd-a1c6-7d3b56dd3220" src="https://github.com/user-attachments/assets/4085fe46-3b9d-42e9-a1ed-810a3c7ec3ff" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="883" height="201" alt="514893389-f8fda907-2d6f-48d2-8124-302485af5941" src="https://github.com/user-attachments/assets/69d57188-da52-40b1-aeb1-775e0c8bd215" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="853" height="89" alt="514893413-52537d96-10d4-463e-8317-3a4ab504a631" src="https://github.com/user-attachments/assets/c5a3caf4-3a35-41b2-9127-e3c4648c399e" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="829" height="404" alt="514893453-1cda8255-1162-4ae3-b2b2-6e3c3a265922" src="https://github.com/user-attachments/assets/69d8acf1-32b6-4c88-9a8e-7c001fa9f96b" />


# RESULT:
The commands/batch files are executed successfully.

