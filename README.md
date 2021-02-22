Goals of This Assignment 
Through working on the image uploader, you’ll get a chance to experience what it is like to join an engineering team as a new, junior software engineer. Specifically, you’ll get a chance to familiarize yourself with the codebase by fixing a few bugs in the codebase. You’ll also get a chance to implement a few well-defined features to the image uploader and improve its functionalities.

Lastly, this project will also introduce you to new concepts to Spring MVC, JPA, PostgreSQL and unit testing. Some of these concepts will be explained to you, and some concepts, you need to Google and Stack Overflow to learn those concepts on your own. This experience will further enhance the experience of joining a new team as a junior software developer as mentioned above.

 

Stub File
As all of you have implemented the ‘Image Hoster’ project given in MVC architecture and Database & ORMs assessments, you will continue working on the same project as a part of this assignment. 
Let us discuss in brief, the features implemented in the ‘Image Hoster’ project till now.

The application runs on localhost and the user is redirected to the landing page of the application displaying all the images in the application.
A new user can register in the application by entering the details such as username, password, full name, email address, and mobile number, and after the successful registration, he is redirected to the login page.
The user can log in the application by entering the username and password, and after successful login to the application, the user is redirected to the user homepage, displaying all the images in the application.
After a user successfully logs in the application, he can click on the title of any image and the image details will be displayed including the description and tags of the image, along with the option to edit and delete the image.
A user can also upload the image by entering the details such as image title, description, image file, and tags related to the image.
You may register in the application and upload the images in the application, to check all the features discussed above.
ImageHoster_assignment_stubfile_download	Download
 

Instructions:
You must manually create a database named ‘imageHoster’ in PostgreSQL with the user as ‘postgres’ using pgAdmin as the UI.
Change the username and password in the stub file in the ‘src/main/java/imageHoster/config/JpaConfig.java’ file and ‘src/main/resources/META-INF/persistence.xml’ file according to your PostgreSQL username and password. 
Note that it is mandatory to assign at least one tag/category to an image while you upload the image. If you do not assign any tag to the image, the image will get uploaded in the application. But when you try to edit the image, the application throws an error. 
