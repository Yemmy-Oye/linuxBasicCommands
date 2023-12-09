# linuxBasicCommands
A brief explanation of Linux Operating System and its Commands
## Linux Operating System  
Linux is an Operating System (OS) like Windows and others. It is an essential part of DevOps as it is presently the most widely used OS in the world. Websites, Android phones, Applications and a lot more runs on Linux operating System.Linux was created by Linus Tovalds in 1991.He was a Computer Science student in the University of Helsinki in Finland when he cloned Unix to create Linux. However, unlike Unix which was a Closed source operating system,Linux is an open source Operating System. It is free for everyone to use. There are many distributions of Linux like Ubuntu, Kubuntu, CentOS, Red Hat, Fedora and others. All these run similar basic Linux commands. Below are some of these basic commands and their functions.  

## Linux Basic Commands  
The distribution for this exercise is Ubuntu 22.04 LTS. For each of the commands, the function will be stated and this will be shown as it appears on the Terminal window with its output.  

1. **mkdir** - This is used to create new directory. *mk* is from make while *dir* is an abbrevaition from directory.
   To make a directory named DevOps, you will type *mkdir DevOps* on the Terminal and press the Return buttton on your keyboard. Note that to run any command on the Linux terminal, you
   must press the Return button after typing the command

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/b6df9eca-5774-4792-827c-226ae2ab6401)


2. **ls** - It is used to list directories and files in a directory.
   To check if the directory created above, DevOps have actually been created, type *ls* on the Terminal

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/b5d87da9-b05a-4390-9b69-efe657489b3b)

     

3. **cd** - The command means *change directory*. As the name indicate, it is used to navigate into a directory or file.
   To navigate into the *DevOps directory*, type *cd DevOps* on the Linux Terminal

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/f7cc2b24-6ee8-49ad-8a7d-197850d74d35)

4. **touch** - It is used for creating files in directories. To create a file named *file1* in *DevOps directory*, type *touch file1* and use *ls* to confirm that the file has been 
   created

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/7316087e-c612-4f79-9c4b-3ef8588ebe91)

5. **vim** - It has two uses.First, it can be used to edit file. It is a text editor in Linux. It can also be used to create file.
   For example, to use the commnad *vim* to edit *file1* created earlier, type *vim file1*.

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/c1554a8a-0174-4ccc-b421-99f653acd023)

   After pressing the return button, the screen will switch into editor mode, then press *i* on your keyboard to be able to enter text in the file

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/c0acbd06-6733-45cc-871e-88ef7b2e97f9)

   To use *vim* to create a new file, for example, *file2*, type *vim file2*

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/d33cb936-f271-4091-aaf3-3a0cb6290c38)
   
   Press the return button and then *i* and enter text in the file.To exit the file, press *Esc* on the keyboard, and enter *:wq*

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/f8760fc5-267a-4130-a29d-cc428721980f)

6. **:wq** - This will save the text entered in the file and also create the file. Using the command *ls* will help to confirm that the file has been created as shown below.

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/a8c337cc-17e3-4fff-ac77-d095bc0c27f7)

7. **cat** - This command is called the concatenate command. It is used to view the contents of files as seen in the image above showing the contents of *file2*. It can also be used to create and concatenate file

8. **rm** - To delete or remove a file in Linux type this command together with the filename. For example, to delete *file1* create above, type *rm file1*.Then use the command *ls* to confirm if the file has been deleted as seen in te image below

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/84ab23ca-7d2f-418f-b9a5-f04bf70a9bf4)

9. **rmdir**- This is an abbreviation meaning **remove directory**. The command is used to delete a directory. To delete a directory with **rmdir*, two conditions must hold.
   - you must not be in the directory environment,if you are in the directory environment use the command *cd* to leave the directory environment
   - if the directory contains files, you have to delete the files before you can delete the directory. This means that *rmdir* can only be used to delete empty directories
   This is illustrated in the image below

   ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/4219a4e4-3f4b-459b-8c35-336296f705e8)

10. **rm -r** - It is used to delete a directory that is not empty together with its contents.For example, for a Directory *DevOps2* containing *file1* and *fileB*, see the image below illustrating how *DevOps2* was created and deleted

    ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/5c67b8ed-bf47-40cc-bf51-d8ae738ecc82)

    ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/c3b76f5d-7f3b-4af8-9033-586ecea86e10)

11. **sudo su** - To log in to the root environnent, use this command.It is important when you need to perform any administartive task. Adminstrative tasks include User management,package management, system configuration, User autentication, Firewall configuration etc

12. **pwd** - This command means *print working directory*. It is used to show the full working path of a file.

     ![image](https://github.com/Yemmy-Oye/linuxBasicCommands/assets/129787413/e6aa53d2-c5a1-439c-a85b-318ad705845f)

13. **clear** - This used to clear the terminal screen when it is full

14. **history** - To show all the commands that has been used on Linux terminal, just type *history*

15. **useradd -m** - To create a User in Linux and create a home directory for the User, type *useradd -m* and the User name.This is an administrative task, therefore you must be in the root environment before you can create a User. For example, to create a User named Richard and home directory for Richard, see the picture below

    

     




   
 

17. 




    
    



   

    
