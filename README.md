Name: Hemant Baghel
Company: CODE ALPHA
ID: CA/JL1/20299
Domain: C++ programming 
Duration: 15 July to 15 August
 


Overview of the Project

Project: Creating a LOGIN AND REGISTRATIONSYSTEM using C++ programming

Objective:
Create a Login and Registration System using C++ that allows users to register with a username and password, and then log in using those credentials.

 Key Points:
1. Registration Functionality: Allows users to enter a username and password, creates a text file with the username as the filename, and stores the username and password in the file.
   
2. Login Functionality: Users can enter their username and password to check against the stored credentials. If the credentials match, the login is successful; otherwise, an error message is displayed.

3. File Handling: Uses `fstream` for file operations (`ofstream` for writing during registration and `ifstream` for reading during login).

4. User Interaction: Provides a menu-driven interface in `main()` to choose between registration and login.

Functions:
- registerUser():
  - Prompts the user to enter a username and password.
  - Creates a file named `<username>.txt` and writes the username and password to the file.
  - Provides feedback on the success or failure of the registration process.

- loginUser():
  - Prompts the user to enter their username and password.
  - Opens the corresponding file (`<username>.txt`) and reads the stored username and password.
  - Checks if the entered credentials match the stored credentials and provides feedback accordingly.

# OUTPUT-
![WhatsApp Image 2024-07-28 at 23 06 30_cba271da](https://github.com/user-attachments/assets/549c285c-3f72-4084-a9bc-fd939bcc20ec)
