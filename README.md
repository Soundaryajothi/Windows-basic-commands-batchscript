# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/90a882dc-e2f6-4eb0-abcd-536cad349feb)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/7bae9532-9eb7-4c95-bfa7-1d6f181e688a)
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/65cfe607-24d7-424c-8201-ff13042f2c7e)




## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/f7d3d4be-12a2-4a07-9312-6f023f10ff9f)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/7cb52ba7-c77f-42bb-b72b-67261f9b39c7)
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/f534201a-ddc9-4aaa-9f68-656e4a9b558b)






## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/33c66ed1-8031-44c7-8d18-885f3fe95c0b)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx 
%userprofile%\Desktop\DocBackup echo Backup completed successfully!


## OUTPUT

![image](https://github.com/Soundaryajothi/Windows-basic-commands-batchscript/assets/144870490/690150de-e2c3-4881-9f9a-21c8b1691463)







# RESULT:
The commands/batch files are executed successfully.

