FaceRecognition
===============

Brief: A Java application for face recognition under expressions, occlusions and pose variations.

Description:

-> We have developed this prototype model with the goal of improving recognition accuracy and reliability under

   un-cooperative scenarios like expressions, occlusions (obstacles like spectacles) and pose variations (<60deg).
   
-> The project is tested with Bosphorous Database (http://bosphorus.ee.boun.edu.tr/default.aspx).




********************************************Steps to execute the project:*************************************************

1. Make sure that latest version of JDK is installed in your system.

2. Check for NetBeans, if not installed, please install the same.

3. Go to Control Panel->Add or Remove Programs(Uninstall Programs) and

   check any other databases are installed (e.g. Microsoft SQL or simply MySQL).

   If so, uninstall all.

4. Install Microsoft Visual C++ Redistributable Packages (vcredist_x86.exe).

5. Intall Wamp Server and make sure that it is running.

6. Open NetBeans and create a new Java project. Delete the default package created.

   (For example, if the project name is abc, then NetBeans automatically creates

     a package with the same name along with a .java file. Delete the complete package

     in Source Packages section ).

7. Open code and copy full "src" folder(Parent folder of all .java files) and paste it on Source 

   Packages in NetBeans.

8. Now right click on Libraries and choose Add JAR/Folder option and open the "libs" folder

   that came with code. Select all(CTRL+A) and click Open.

9. Copy all .dll files came with code in the "dll" folder to C:\Windows folder [ ONLY FOR 32 BIT SYSTEMS].

10. Install Java 3D API(java3d_1_5...exe).

11. [ ONLY FOR 64 BIT SYSTEMS ] Go to C:\Program Files\Java\Java3D\bin and copy all DLLs to C:\Windows.

12. Open System Tray->Wamp Server green icon->Left Click->MySQL->MySQL Console. Press Enter.

    You should see mysql> prompt.

    Enter the following command:

    create database 3dface; [Enter]
 
    use 3dface; [Enter]

    create table users(UserName varchar(30),Email varchar(50),Phone varchar(10),Password varchar(20)); [Enter]

    exit; [Enter]

13. Again open system tray->Wamp green icon left click->phpMyAdmin.

    Browser will be opened. Database list on left side. Click on "3dface".

    You can see "users" table and get confirmed with the same.

    
12. Yeah!! All set! You are done and run the project.



License: See License.txt


**************************************************************************************************************************
