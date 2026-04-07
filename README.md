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
<img width="410" height="35" alt="Screenshot 2026-04-07 094158" src="https://github.com/user-attachments/assets/b818eb2a-0f6c-4328-9f7d-a864511dc8c2" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="374" height="40" alt="Screenshot 2026-04-07 094207" src="https://github.com/user-attachments/assets/efa727ff-7a68-4f95-ba01-2153e31953ae" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="552" height="129" alt="Screenshot 2026-04-07 094636" src="https://github.com/user-attachments/assets/cca05bda-5070-4f6c-a331-b8ca92e2948d" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="672" height="227" alt="Screenshot 2026-04-07 094642" src="https://github.com/user-attachments/assets/999444f4-a1be-4b35-bc4c-edd6c4fe30fe" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="530" height="123" alt="Screenshot 2026-04-07 094800" src="https://github.com/user-attachments/assets/47b4f21d-84c5-414f-b8d2-09349a59afa3" />


Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="465" height="46" alt="Screenshot 2026-04-07 094930" src="https://github.com/user-attachments/assets/f0be58d9-73de-40cd-b514-fa2fce0319ab" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="657" height="165" alt="Screenshot 2026-04-07 094935" src="https://github.com/user-attachments/assets/6cbd371a-fcdb-49ad-a756-6619baa2d879" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="919" height="646" alt="Screenshot 2026-04-07 095142" src="https://github.com/user-attachments/assets/dc2141f6-3d17-4eeb-8d79-fe4a32c16f33" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="671" height="192" alt="Screenshot 2026-04-07 095220" src="https://github.com/user-attachments/assets/6ca29e94-ad73-4d82-a9bb-49fa425c40d2" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="542" height="125" alt="Screenshot 2026-04-07 095824" src="https://github.com/user-attachments/assets/69dca099-0924-490f-9651-3c0eccdd4d68" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

## OUTPUT
<img width="689" height="175" alt="Screenshot 2026-04-07 095938" src="https://github.com/user-attachments/assets/ae7b513a-bbfa-48d5-b7d4-152a6acd8fba" />

Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.
## OUTPUT
<img width="547" height="208" alt="Screenshot 2026-04-07 100034" src="https://github.com/user-attachments/assets/cd74af6a-4252-41b0-9fe0-2e9a36fb6082" />

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="680" height="248" alt="Screenshot 2026-04-07 100235" src="https://github.com/user-attachments/assets/28bb5371-d984-4dc4-b40e-5f12fe24f09d" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="795" height="505" alt="Screenshot 2026-04-07 100336" src="https://github.com/user-attachments/assets/7af75518-48c8-4333-9607-4dbf2949ec08" />

# RESULT:
The commands/batch files are executed successfully.

