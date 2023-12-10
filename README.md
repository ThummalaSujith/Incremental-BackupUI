# Incremental File Backup and Recovery System
Incremental File Backup and Recovery System. This user-friendly solution prioritizes incremental backups to optimize storage and streamline recovery. Timestamped backups facilitate organized data management, ensuring users can easily trace and restore specific file versions. The intuitive interface caters to users with diverse technical backgrounds, simplifying the backup and recovery processes. Leveraging Java for cross-platform compatibility, the system employs ZIP compression for storage efficiency.

This Java program provides an incremental backup system with a graphical user interface (GUI) for easy interaction. It allows users to choose source and backup folders, perform backups, and recover files from previous backups. The program creates timestamped backup folders, ensuring multiple backups can be created over time.

System requirements : VSCode, JDK

[To Install VSCode Click Here](https://code.visualstudio.com/download)

[To Install JDK Click Here](https://www.oracle.com/java/technologies/downloads/)


![Alt text](image.png)

1.Run the Program: Execute the Java program (IncrementalBackupUI) by running the main method. The graphical user interface (GUI) will appear.

![Alt text](image-1.png)

2.Java swing UI will show this window

![Alt text](image-2.png)

3.Choose Source Folder:Click on the "Choose Source Folder" button. Select the folder containing the files you want to back up.

![Alt text](image-3.png)

4.Choose Backup Folder:Click on the "Choose Backup Folder" button. Select the folder where you want to store the backup files. The program will create a subfolder within this location with a timestamp.

![Alt text](image-4.png)

5.Perform Backup:Click on the "Backup" button. The program will copy files from the selected source folder to a subfolder within the chosen backup folder. It will only copy files that are newer than the existing ones in the backup.

![Alt text](image-5.png)

6.Check Backup:Open the chosen backup folder to verify that the new backup subfolder has been created, containing the updated or new files.

![Alt text](image-6.png)

To recover a backup using the provided Java program, follow these steps:

1.Run the program: ->Execute the Java program (IncrementalBackupUI) by running the main method. The graphical user interface (GUI) will appear.

![Alt text](image-7.png)

2.Choose Backup Folder: ->Click on the "Choose Backup Folder" button. Select the folder containing your backup files (the folder that was specified as the backup folder when performing the backup).

![Alt text](image-8.png)

3.Recover Files: ->Click on the "Recover" button.

![Alt text](image-9.png)

A dialog box will prompt you to enter the name of the backup to recover from. Enter the name without the ".zip" extension.

![Alt text](image-10.png)

4.Wait for recovery: ->The program will unzip the selected backup and restore the files to the original backup folder. You will see a message dialog indicating the success or failure of the recovery process.

![Alt text](image-11.png)

5.Check Recovered Files: ->Open the original backup folder to verify that the files have been successfully recovered.

![Alt text](image-12.png)

