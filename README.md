# # SyncShareStore
A File Storage and Sharing System


<h3>Overview</h3>

File sharing is one of the oldest applications of the internet. One way of sharing files online is for a user to upload files to a common space on the web and others users can download the files from the common web space. 
The objective of this project was to design an online file sharing website where users can upload files and other users can download them. To attain this objective an advance java enabled interactive user interface involving features like extensive search capabilities was developed. To make the website more user friendly, users were given two space-constrained visualizations of their file system to view space occupied by the files and folders based file management system that works like browsing files on a desktop computer with drag and drop, context menu functionalities etc. 
This report contains all the information that helps user to upload, download and search the files stored in both places and discusses the advantages and disadvantages of both techniques in terms of performance, security, integrity, maintenance and code complexity
For every organization it is important to have files of all person stored at one place. Sync, Share and Store plays a vital role in this situation.

Software Requirements
-------------------
JRE 1.8 and above with Apache server running to run the same on your localhost with MYSQL server for database connectivity.

USAGE
------
The `index_1.jsp` file is the home file that opens up the homepage which has login form redirecting users after matching the credentials. There are 2 links to it. If the username and password is 'admin' and a 'admin@1234' respectively, it will redirect it to the admin page through `ahome.jsp` whereas the registered users would be taken to their respective pages through `shome.jsp`.In this homepage there is a link for knowing about the application contained in the file `abt.jsp` ,a contact link in `contact.jsp`and a link for registration of new users in `cregister.jsp`.
The user' panel has menu bar in the file `studentmenu.jsp` having options to update the profile through `update.jsp`, `showfile.jsp` to display files uploaded by the users, a file `index1.jsp` which has links to file `index2.jsp` and `upload.jsp` to upload files giving an option to make the particular file public or keep them for their use.Also there is an option to delete their files which is in the file `del_file.jsp`. And finally there is a file `searchFile.jsp` allowing searching through keywords. One has a flexibility to either store their files as a public file thereby sharing it with every user of the application, or keep it private for their own usage.
File `ahome.jsp` is a panel for admin where it displays the record of files stored and users registered yet in the application. Apart from this admin can view user details(`ashowall.jsp`),delete registered users through the file `usr_del.jsp` Search user by ID (`asearch.jsp`).


WORKING PRINCIPLE
---------------------
Through this application SyncShareStore, users can upload file of any format and while storing the files they have an option to make it shareable or to keep it private for their own use. If the file is made shareable, other users searching for the similar file can access it otherwise it would remain private for that specific user only.Hence SyncShareStore provides a platform to search files and access them and also to store files according to their convenience.

Applications & Future Scope
----------------------------
This application is used for storing the files of any format be it pnj,jpg,psd,pdf,otd,mp3,mp4,avi,mpeg, etc and make them shareable or keep them private.Also allowing searching files with the help of keywords gives this application another edge.
Future Scopes can include keeping files as well as users private that is allowing specific users to seek files for further use.

<br><br>

Hope you will enjoy running the application.
