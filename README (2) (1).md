# Poisonous Plant Identification System

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation Instructions](#installation-instructions)
3. [Usage Guidelines](#usage-guidelines)
4. [Contribution Guidelines](#contribution-guidelines)

## 1. Project Overview
The Poisonous Plant Identification System is designed to help users identify and differentiate between poisonous and non-poisonous plants. The Poisonous Plant Identification System's main objective is to identify unsafe plants in order to lower the number of fatalities or injuries as a result of plant poisoning. The system uses machine learning algorithms trained on extensive datasets to classify plant images and provide users with accurate information regarding their toxicity. This approach aims to improve public safety and awareness by giving people a fast and dependable way to identify potentially poisonous plants by utilising machine learning technology.

### Main Features
- **Image Classification**: Automatically classify plant images as poisonous or non-poisonous.
- **Toxicity Information**: Provide detailed toxicity profiles and symptoms associated with poisonous plants.
- **User-Friendly Interface**: Easy-to-use interface for uploading images and receiving identification results.
- **Educational Resources**: Include educational content on poisonous plants and safety precautions.

---

## 2. Installation Instructions

 **Install Required Libraries**:
   - Open a terminal or command prompt.
   - Install TensorFlow: pip install tensorflow
   - Install OpenCV: pip install opencv-python
   - Install Flask: pip install flask

 **Clone the Project Repository**:
   - Open your terminal (or Command Prompt on Windows).
   - Clone the project repository from GitHub or obtain it from the designated source.
    ```bash
     git clone https://github.com/yourusername/poisonous-plant-identification.git
	```

 **Setup and Configuration**:
   - Navigate to the project directory
   - Modify configuration files as needed (e.g., database settings, model paths).

 **Set Up the Database**:
   - Ensure you have the database server running (MySQL)
   - Update the database configuration in the project settings
   - Run database migrations to create necessary tables:
       ```bash
       python manage.py migrate
       ```
 **Start the Desktop Application**:
   - Run the Desktop application using the following command:
     ```bash
     python app.py
     ```
   - You should see output indicating that the server is running.

 **Download Dataset and Models** :
   - Download the existing Poisonous Plants identified dataset
   - Train the Machine Learning Model using the dataset

 **Download the Mobile Application** :
   - Download the Mobile Application for users
   - Create an Account for user

### Troubleshooting

- **Dependency Issues**: If you encounter issues while installing dependencies, ensure that you have the correct versions of Python and pip. You may also try upgrading pip:
  ```bash
  pip install --upgrade pip
  ```
---

## 3. Usage Guidelines

### For Users
 **Identify Plants**:
   - Open the mobile app and navigate to the plant identification feature
   - Use the camera to take a picture of the plant or select an image from your gallery
   - Click the "Identify" button
   - The system will process the image and display the plant’s name and toxicity information
   - Results will load after 10-20 seconds
   - Results show the corresponding Poisonous Plants and their details including Toxicity Information. 
 **View Plant Information**:
   - After identifying a plant, the app provides detailed information about the plant, including its common name, scientific name, toxicity level, and safety measures
   - There is also a gallery of Poisonous Plants identified with user-friendly interactions
     
### Experts/Admin
 **Add New Plants**:
   - Launch the Desktop version of the system
   - Log in to the admin/experts interface
   - Navigate to the "Add New Plant" section.
   - Fill in the required information, such as plant name, scientific name, images, and toxicity details.
   - Click "Submit" to add the plant to the database.
   - Admins will verify if submission is from experts or botting
 **Train the Model**:
   - Go to the Machine Learning Section
   - Select Submit Dataset to train the Machine Learning Algorithm for new plants
     
 **Modify System**:
   - Access the admin interface and navigate to the "Modify System" section.
   - Update system settings, model configurations, or any other adjustable parameters.
   - Save the changes to apply updates to the system.
 **user Management**:
   - View, add, or remove users from the system.
   - Update user roles and permissions as needed
   
### Example Use Case and Screenshots

 **Upload an Image**:
   - You have an image of a plant you suspect might be poisonous.
   - Open the mobile app and upload the image.
   - ![image](https://github.com/BillyofBob/SOFTWARE-ENGINEERING-GROUP-11/assets/168271245/1b9a1aa9-ad83-4531-a2a6-67f6d57a69ad)

 **Receive Classification**:
   - The system identifies the plant as poisonous and displays this information.
   - ![image](https://github.com/BillyofBob/SOFTWARE-ENGINEERING-GROUP-11/assets/168271245/e244aae1-6c0b-4f3c-8e4d-4df340455fb7)
 
 **Plants Catalogue**:
   - Displays various types of Poisonous Plants
   - ![image](https://github.com/BillyofBob/SOFTWARE-ENGINEERING-GROUP-11/assets/168271245/4407767b-ca6b-4951-ac1f-6acb43bdfbdb)
  
 **Train Model**:
   - Training the Machine Learning Model
   - ![image](https://github.com/BillyofBob/SOFTWARE-ENGINEERING-GROUP-11/assets/168271245/a8c67353-44c3-4bdc-92f4-b4580c27d56b)

 **User Management**:
   - Admins able to manage users
   - ![image](https://github.com/BillyofBob/SOFTWARE-ENGINEERING-GROUP-11/assets/168271245/9c9856b4-e7cd-4f64-9dfc-2717a5257d9a)

### Additional Features

- **Educational Resources**:
  - Access a library of educational content related to poisonous plants.
  - Learn about various poisonous plants, their identifying features, and safety measures to avoid contact.

- **Feedback and Improvements**:
  - Users can provide feedback on the system's accuracy and suggest improvements.
  - Use the provided contact information to share your feedback.

- **Personal Chats with experts**:
  - Users can interract and enquiry experts of the matter and seek for advices
  
---

## 4. Contribution Guidelines

### How to Contribute

 **Fork the Repository**:
   - Go to the project's GitHub page and click the "Fork" button at the top-right corner. This will create a copy of the repository in your GitHub account.

 **Clone Your Fork**:
   - Clone the forked repository to your local machine using the following command:
     ```bash
     git clone https://github.com/yourusername/poisonous-plant-identification.git
     ```
   - Navigate into the project directory:
     ```bash
     cd poisonous-plant-identification
     ```

 **Create a Branch**:
   - Create a new branch for your feature or bug fix. Use a descriptive name for your branch:
     ```bash
     git checkout -b feature/your-feature-name
     ```

 **Make Changes**:
   - Make your changes to the codebase. Ensure your code follows the project's coding standards and best practices.
   - Write clear and concise commit messages. For example:
     ```bash
     git commit -m "Add feature to identify new plant species"
     ```

 **Push to Your Fork**:
   - Push your changes to your forked repository:
     ```bash
     git push origin feature/your-feature-name
     ```

 **Create a Pull Request**:
   - Go to the original repository on GitHub and click the "New Pull Request" button.
   - Select your branch and the branch you want to merge into (usually `main` or `master`).
   - Provide a clear and detailed description of your changes in the pull request. Include any relevant information that will help the reviewers understand your contribution.

### Code of Conduct

To ensure a positive experience for everyone, contributors are expected to adhere to the following code of conduct:

- **Be Respectful**: Treat everyone with respect and courtesy. Discrimination, harassment, and inappropriate behavior are not tolerated.
- **Be Collaborative**: Work together and be open to feedback. Constructive criticism is encouraged, and differences of opinion should be resolved through respectful discussion.
- **Be Inclusive**: Create an inclusive environment where everyone feels welcome. Encourage diversity and be mindful of different perspectives.

### Reporting Issues

If you find any bugs, have suggestions for new features, or have general questions, please open an issue in the GitHub repository:

 **Open an Issue**:
   - Go to the "Issues" tab on the project's GitHub page.
   - Click the "New Issue" button.
   - Provide a clear and detailed description of the issue or suggestion. Include any relevant information, such as steps to reproduce the bug, screenshots, or examples.

### Style Guide

To maintain a consistent codebase, please follow these coding standards:

- **Python**:
  - Use [PEP 8](https://pep8.org/) as the style guide for Python code.
  - Write clear and concise docstrings for functions and classes.
  - Use meaningful variable and function names.

- **JavaScript** (if applicable):
  - Follow [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) for JavaScript code.
  - Ensure code is well-documented with comments where necessary.

### Testing

Ensure that your changes do not break existing functionality:

 **Write Tests**:
   - Write unit tests for any new features or changes. Ensure that your tests cover edge cases and are well-documented.

 **Run Tests**:
   - Run the test suite to verify that all tests pass before submitting your pull request:
     ```bash
     python -m unittest discover
     ```







