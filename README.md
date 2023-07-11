# AdmissionQuiz - C# Windows Forms App college project (Node.js)

This repository contains the source code for AdmissionQuiz, an application which is a set of math/computer science tests developed in Visual Studio 2019 IDE. The tests aim to assess the user's knowledge for the admission exam of the Faculty of Automatic Control and Computers. The application follows the Model-View-Controller (MVC) architectural pattern. It is written in C# and designed as a Windows Forms application.

The project was implemented together with [aeerdna01](https://github.com/aeerdna01) and [stefana17](https://github.com/stefana17).

## Technologies 
- C# Windows Forms App (.NET framework)
- Class Library (.NET framework)
- Unit Test Project (.NET framework)
- DB Browser (for question and users storage)
- HelpnDoc (for user documentation)
- Doxygen (for developer documentation)

## Features
- **AdmissionQuiz**: The AdmissionQuiz application provides a set of tests similar to the ones used in the admission process of our faculty. Users can take these tests anytime to assess their level of knowledge.
- **Subject Selection**: Users can choose between two subjects: Mathematics or Computer Science.
- **Question Format**: Each test consists of 10 questions based on the selected subject. Each question has four answer options, with only one option being the correct answer.
- **Time Limit**: Before starting the test, users can select the amount of time they need to complete it (implements with Strategy design pattern).
- **Scoring and Results**: At the end of the test, the application displays the number of questions answered correctly. It also provides a "Rejected" or "Admitted" status message based on the score. Users have the option to review their answers, return to the subject selection page, and take another test.
- **Database Connection**: The application maintains a global instance of the database connection class implemented using the Singleton design pattern. This instance allows all modules within the application to access the database connection and perform CRUD operations on the respective tables.
- **Quiz State Management**: The application utilizes a global data structure implemented using the State design pattern to manage the quiz state. This allows for seamless navigation between quiz questions and tracks the user's progress

## Documentation
- [Software Requirements Specification (SRS) and Software Design Document (SDD)](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Documenta%C8%9Bie/Documenta%C8%9Bie.pdf)

## Diagrams

- [Activity Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/1%20-%20Activity%20diagram.png)
- [Class Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/2%20-%20Class%20diagram%20.png)
- [Package Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/3%20-%20Package%20diagram.jpg)
- [MVC Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/4%20-%20MVC%20diagram.jpg)
- [Sequence Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/5%20-%20Sequence%20diagram%20v1.png)
- [Use Case Diagram](https://github.com/Carla-Husman/AdmissionQuiz/blob/340431f8378e3c5d6c5086a6f4e3239d632d19eb/Documentation/Diagrame/6%20-%20Use%20case%20diagram.png)

## DataBase
![image](https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/d88b6786-74ea-4f28-9241-af962f5cb5e2)


## Screenshots
### Menu form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/36c36390-5dd5-40bb-bb27-88e5a1794153" width="500" height="300">

### Login form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/f0f92790-f4c4-4a50-8871-978ad3d5ed4a" width="500" height="300">

### Options form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/a13a6f60-1b46-4147-a6fb-86b1d2383f3f" width="500" height="300">

### Settings form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/e934014c-dbc6-4385-9a40-1e4e76e8bc9c" width="500" height="200">

### Test form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/f4f0f907-c450-4a6c-982a-c6168b72c79f" width="500" height="300">

### Result form
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/5aa73c28-d862-4991-8d51-7003d99fb572" width="500" height="300">

### Help
<img src="https://github.com/Carla-Husman/AdmissionQuiz/assets/125916556/6fa1b0b5-fa4b-468e-98e9-198126ae1097" width="700" height="300">








