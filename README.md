# Art-Gallery-Management
Using Java Swing and AWT the art has been managed in the DataBase.

The purpose of Art Galley Management is to automate the existing manual system by the help of a JAVA GUI application, fulfilling their requirements, so that their valuable data/information can be stored for a longer period with easy accessing and manipulation of the same. JAVA GUI software is an easily available and easy to work with. This application was created using Java Swing and Components of AWT.        Art Gallery Management can lead to an error free, secure, reliable and fast management system. It can assist manager to concentrate on their other activities rather than record keeping. Thus it will help organisation in better utilization of the resources. The organisations can maintain computerized records without redundant entries.
The main objective of this project is to manage details about art paintings and admins in an efficient manner. The purpose of this project is to build an application program to reduce the manual work of managing art paintings and their details.
The Art Gallery Management provides the following functionalities :
  >	Add a Admin.
  >	Add an art painting.
  >	Remove an art painting.
  > Update details of an existing art painting.
To use these functionalities an existing admin must login first by clicking on the login button. Login will be successful if the username and password provided by the admin matches with the ones saved in the database. If the details do not match, an ‘Invalid User’ message will be displayed and the user will have to enter the details again. 
The paintings are uploaded to one of the four categories :
  >	Abstract art.
  >	Portraits.
  >	Landscapes.
  >	Still life.
The images links are not uploaded on the database but they are accessed by their type and the title to display the images. All the details of art paintings can be retrieved from the database and updated easily. 
Home page :
User can search the images on the bases of their titles.And the image will be displayed in the belove label.
First the title will be checked in teh database is the image doesn't exist the "Painting not found" dialogue box will be displayed.
Admin Login :
Username and Password are checked with the existing ones in the database.
If the details do not match, an invalid password message will be displayed. Clicking on the cancel button will take the user back to the home page.
Add an Art :
If the admin is valid then add an art page will be opened. To select an art piece, Folder button should be pressed, this opens a browse window to select the image we want to upload. After selecting the image, Open Button should be pressed to upload the URL of the image in the above text field. And then the upload should be clicked to see the preview the image in the above label. On clicking Add Art button the details will be added in the database. And Cancel button will clear all the fields and details will not be uploaded.
Remove an Art :
The second option is to remove an art piece existing in the database. First from the search textfield user can search for the art. If the art piece exists in the database, its details would appear in all the below fields automatically. Clicking on the remove button will remove the image details from the database. Cancel button will clear all the fields without removing the details.
Update an Art:
To update an existing art piece first select the art piece from the search field. The details of the art piece would appear automatically. Any of the details can be changed. Update Button would update the details in the database. Cancel button will clear all the fields without updating the details.
Add another admin:
To add another admin, all the fields need to be filled. Clicking on the Add Admin Button will add a new admin to the database. This user can then login as an admin later to ascess the other features. Cancel Button will clear all the fields without adding the details.
And at last the log out button is provided to loggout from all the pannels and go to the home page.\
  > This project is created on one Frame Multiple Pannel system. 
