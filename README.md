

Project Overview
The goal of this task was to design a functional and aesthetically aligned graphical user interface (GUI) for a basic user login form. No backend logic (credential validation) has been implemented yet.

Key Features Implemented
GUI Framework: Java Swing

Development Environment: NetBeans IDE (using the Design Window and Palette)

Form Name: LoginForm (or LoginScreen)

Core Components:


Title: JLabel set to "Login Page" (Font customized to Bold, 24px) 


Username Field: JTextField (Variable Name: usernameField) 


Password Field: JPasswordField (Variable Name: passwordField) 


Login Button: JButton (Variable Name: loginButton) 


User Experience: ToolTip text is provided for both input fields.




Layout: The form is designed for uniform width (≈200px) and clear vertical alignment.


Centering: The window is set to open centered on the screen.


How to Run the Project
Open NetBeans IDE.

Go to File > Open Project and navigate to this folder. Select the project folder (e.g., LoginApp).

Once the project is loaded, locate the JFrame form (LoginForm.java or LoginScreen.java) in the Source Packages folder.

Run the project by pressing 

Shift + F6 or by clicking the Run button in the toolbar.

The form will appear centered on the screen, ready for the optional next step of adding credential validation logic.

Next Steps (Optional Functionality)
To add functionality to the "Login" button, you would:

Double-click the 

loginButton in the NetBeans Design View to auto-generate the event handler.

Implement the Java code within that handler to retrieve text from 

usernameField and passwordField and validate the credentials (e.g., against hardcoded values or a database).
