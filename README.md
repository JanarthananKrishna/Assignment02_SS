# Uploading a file to Google Drive Using OAuth Access Token

This project is based on implementing a web application that consumes the service of an OAuth Authorization Server and an OAuth Resource Server.
You can download this project and use this for testing purposes.

Implementation of the project.

**1.Download this project as a .zip file.**

**2.Then sign into your Google account and go the following link to enable Google Drive API.**
https://developers.google.com/drive/api/v3/quickstart/php

![enable_drive_api](https://user-images.githubusercontent.com/31270985/56876997-bfe35300-6a68-11e9-8bfe-98a7d76b0090.PNG)

**_(This will allow you to use credentials for a quickstart project. If you want to enable it for a customized project you'll have to enable it using Google developer's API console) https://console.developers.google.com_**

![api_console](https://user-images.githubusercontent.com/31270985/56877366-105bb000-6a6b-11e9-881e-296a67682aef.PNG)





**3.Download credentials.json file**


![json_download](https://user-images.githubusercontent.com/31270985/56878028-82ce8f00-6a6f-11e9-8b11-e90ad35f2bec.PNG)





**4.Download Google API PHP client .zip file using this link.**
https://github.com/googleapis/google-api-php-client/releases


![apiclient download](https://user-images.githubusercontent.com/31270985/56878031-83672580-6a6f-11e9-9056-2157b1dc4330.PNG)






**5.Extract the downloaded project into WAMP/XAMPP server path.**
(C:\wamp64\www) or (C:\xampp\htdocs)



**6.Extract Google API PHP client .zip file. And copy 'src' and 'vendor' folders into root folder of this project.**
(Root=C:\xampp\htdocs\Assignment02_SS)


![copy_srcand_vendor](https://user-images.githubusercontent.com/31270985/56878026-8235f880-6a6f-11e9-8704-e110e88d691f.PNG)





**7.Copy credentials.json file to Root folder and rename it as 'oauth-credentials-file.json'**

**8.Now run your Web app using Apache server**
(http://localhost/Assignment02_SS)



![sign_in_first_page](https://user-images.githubusercontent.com/31270985/56877002-c1ad1680-6a68-11e9-8e8f-1986a7476ce2.PNG)







**9.Press 'Sign in with Google' button and proceed. You'll ask permissions by Google Drive API for file management.**




![grant_permission_confirm](https://user-images.githubusercontent.com/31270985/56878027-82ce8f00-6a6f-11e9-90d6-33b5d018bbea.PNG)








**10.As a final step you can upload files to Google Drive Using 'Choose file' button. If the upload is successfull 'Your call was successfull' message will appear.:+1:**









![select_file](https://user-images.githubusercontent.com/31270985/56877001-c1148000-6a68-11e9-9989-ebb9fb0ad6ed.PNG)

![upload_completed](https://user-images.githubusercontent.com/31270985/56878029-83672580-6a6f-11e9-95db-d4101835acf3.PNG)

