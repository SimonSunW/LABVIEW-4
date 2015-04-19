

Procedure to use this VI:
              1) First Choose a File Path where you want to store the Image Snaps taken from the Microscope. 
              2) Now, Choose a Sample_Folder Name for example: "Sample_Folder" or any name your are comfortable with.
              3) Then, Choose a Sample_File Name for example: "Sample_File_Name" or any name your are comfortable with.
                 (While Naming the Folders/ Files please use a '_' in place of space. Because it is a good practice of naming files/Folders) 
              4) Set how many snapshots you want to take using the CCD Camera mounted on the Microscope.
              5) Now, set the timer for each Snapshot. Remember: the units of time here is in Milliseconds.    
             6) RUN THE PROGRAM AND SEE THE RESULT in the chosen File Path.

How this VI Works:

             For example you choose a folder name called "Sample_Folder" and File Name Called "Sample_File_Name". And, now you choose no. of snapshots and timer between each snapshot then,   RUN THE VI. 
             
            The Program first tries to see, if there is any folder named "Sample_Folder", if there is any folder with the same name in the chosen directory then it creates an another folder incremental version name as "Sample_Folder(1)" etc. else it creates a folder with a desired name. And after creating an appropriate folder name, the program then creates files as "Sample_File_Name1" and so on.

               FOR BETTER UNDERSTANDING PLEASE RUN THE PROGRAM AND SEE THE OUTPUT             

          
                                                                                                                            
