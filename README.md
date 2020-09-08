# SQLEditor
This is a free, online and easy-to-use SQL Editor, where you can type and execute SQL commands.

The program consists of 4 main sections:

  A. The central Working area, where you will type your code. 
  
  B. The Menu bar. The Menu bar is further divided into 3 parts:
  
     a. The File submenu. This submenu contains file-related options, like starting a new file, opening an existing file or saving a file. Please note that if you try 
        execute the code from an earlier file, you might get some error, if that code was run earlier. This is because, trying to run the code again means that you are
        trying to create the same table once again (for example), hence you will get the error. Also, the extension compatible with this software is '.sqle'.
        
     b. The Execute submenu. From this submenu, you can execute your code. Please note that to display the table, you have to either type "SELECT * FROM table_name" in
        the working area, where 'table_name' is the name of the table, or you can click on the "Display Table" option and type in the table name.
        
     c. The About submenu. Here, you can get the information about the creator of this software, and its current version.
     
  C. The Status bar. This displays the status of each command you have executed. If there is an error, the status bar turns red.
  
  D. The Console window. This is where the table will be displayed.
  
This software was created using Python and the following modules:
   a. SQLite3 
   b. TKinter
   c. OS

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
I hope this software meets your SQL needs! I will be updating the software with new features, so stay tuned!

Version 1 - Completed on September 1, 2020.
Made by Hardik Medhi, an undergraduate student at REVA University.
If you come across any bugs, or you want to provide feedback, please email me at: hardikmedhi21@gmail.com
