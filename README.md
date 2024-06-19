# rn-assignment4-1103846333
 
Overview
Jobizz is a job search application that helps users find their desired job positions. The app consists of two main screens: LoginScreen and HomeScreen, and a reusable JobCard component to display job details.

Components
1. LoginScreen
The LoginScreen is the initial screen of the app. It allows users to log in by entering their name and email. Upon successful login, the user is navigated to the HomeScreen.

Usage: Displays a login form with input fields for name and email. It includes a login button that navigates to the HomeScreen with the entered name and email as parameters.

Screenshot:
![Screenshot 2024-06-19 194535](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/811a8ffb-cfa9-429b-81e0-60c6aca523de)

2. HomeScreen
The HomeScreen is displayed after the user successfully logs in. It shows the user's name and email at the top, followed by a search bar for job search. Below the search bar, there are two sections: "Featured Jobs" and "Popular Jobs", each displaying a list of job cards horizontally and vertically, respectively.

Usage: Displays the user's details, a search bar, and lists of featured and popular jobs using the JobCard component.

Screenshot:
![Screenshot 2024-06-19 195133](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/dde7fa43-c5c1-4595-902b-8cad0bfa0b7a)

3. JobCard
The JobCard is a reusable component used within the HomeScreen to display individual job details such as title, company, salary, and location. Each job card includes an icon representing the company.

Usage: Displays job details in a card format. Used in the HomeScreen to list featured and popular jobs.


Navigation
The app uses React Navigation to handle navigation between the LoginScreen and HomeScreen.

LoginScreen:

Displays a form to enter name and email.
Navigates to HomeScreen with name and email as parameters upon successful login.

HomeScreen:
Displays the user's name and email.
Provides a search bar for job search.
Lists featured and popular jobs using JobCard components.

Assets
The app uses various icons for companies and a profile image

![facebook](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/6bed7fec-1612-44bb-880b-932aa8ecc020)
![burgerking](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/1ccd6ce2-c6c4-46aa-bf2b-a2ac56d2ad00)
![beats](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/5eeb2eed-0bfd-4005-b61f-5517b6b71803)
![apple](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/8cba792b-4f09-4624-ba25-f72666f76e81)
![amazon](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/76b061cb-a116-4cda-8db3-40051213aad9)
![adaptive-icon](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/f9bbe798-62ee-427f-90d0-50c26834d0c9)
![twitter](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/e0b39ba4-7c19-41ba-ab9b-47570be01169)
![spotify](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/cb569c9e-aa26-4533-bb61-7ee54cafdfcd)
![splash](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/5d9ffd73-4d12-45a7-92a5-7ea08f44b49e)
![netflix](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/796f94cb-bc75-4eb8-87c8-3a1b784094d2)
![microsoft](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/b5e65558-d2f2-4def-abe9-bf6eedfb1ba5)
![icon](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/5608b0f4-2e9a-4fc0-be1e-bf1c8b2fad32)
![google](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/c05c41ad-187d-4a0a-a25b-1e5ecb66ee79)
![profile](https://github.com/davidkandaaaa/rn-assignment4-11038463/assets/149037120/09c56ecc-11ac-43c2-8006-cd0417b049a5)


Conclusion
Jobizz provides a simple and efficient way for users to search and apply for jobs. With a user-friendly interface and comprehensive job listings, it aims to streamline the job search process.
