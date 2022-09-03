# Login-Application
Date of Creation: 29.03.2022

CSM 2020-24

Anil Neerukonda Institute of Technology and Sciences

**People involved:** 

* 320126552027      Surakattula Goutham 
* 320126552023      Neelamsetty Sai Venkata Rushikesh ( Team Leader )
* 320126552004      Buddala Devi Lalli Sri 
* 320126552007      Dodda Sai Sirisha  
* 320126552011      Garimella Sree Harshitha
* 320126552029      Vadali Aishwarya 

# Aim of the project
To design a login page containing the fields of user name and password where the user needs to enter details to the fields where the password is verified for a valid user. If the password is correct then the user must be directed to a new page.

# Abstract

In the Login page you can register yourself with a username and password, after registering yourself you can login using the login page.
When you press the register button it will open a new frame in which you can register yourself.
When you register yourself the data of that particular user will be stored in a text file.
If you want to register then you can enter username, password and confirm password.

When you enter your username you can have any type of characters or numbers, but it should be different from others. When you enter username and password and press submit. It will check the file and find if the username already exists. If the username exists then it will show you “Username already exists” otherwise it will store your details in the file.

Password and Confirm Password should match otherwise it will display the text ”Passwords do not match”.
The password must be more than 9 characters and it should contain at least one lowercase letter, uppercase letter, number and a special character. If any of these conditions are not met, the registration will not be done and it will show that the password should contain more than 9 characters and at least it should contain a lowercase letter, uppercase letter, number and a special character.

If we select show password the password field is displayed with readable text otherwise it is hidden.
If username, password and confirm password are accepted then the details will be stored in a text file named LoginData.
While storing in a file it encrypts the data using Base64 encryption and stores it inside the file so that no one could see the login details of the users.
After registration, if you enter the correct username and wrong password then, it will show that you have entered wrong user credentials and won’t let you in.

If you enter the wrong username then it will show you that you haven’t registered.
When you try to login using correct login credentials it will open a new frame and welcome you to the page.
By this we complete the registration of a user.

# Components Used 
1.	JPasswordField 
2.	 JButton 
3.	 JTextField 
4.	Checkbox 
5.	 JLabel 
6.	 JFrame 
7.	 ActionListener 
8.	WindowListener

# Project Specifications
*	Each section of the project i.e, Registration section, Login Section and Successful Login section each have distinct frames. Frame transition is achieved by alternately changing the visibility of the frames so that only the required frame is visible while the rest of the frames, even though they are present, are invisible. 
*	If unregistered it will prompt a “You haven’t registered yet” message on the label present in the login frame.
*	Usage of frame transition from one frame to another while logging in and registering.
*	While registering, the password must contain at least one capital letter,a special character, a number and should be at least 10 characters in length.
*	Re-entering the password is required to ensure that the user is entering the password without any mistakes in it.
*	Once the username is entered it is checked whether it already exists in the database so that there is no ambiguity while logging in.
*	While storing the credentials it is encrypted using Base64 encryption so that even when the LoginData file is opened by a third party he/she is unable to read the contents.

