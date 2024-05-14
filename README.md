# MOBILE ANTI-THEFT SYSTEM

### There are 3 things implemented in this project :
1. A website to show the impact of Mobile theft, Various mobiles and Data collected for mobiel theft.
2. Mobile Anti-Theft System Applications to detect the Mobile Theft in serval ways.
3. A Python notebook (Colab) to show the analytics through Machine Learning models based on a similar dataset.

## ABSTRACT :

The project focuses on the domain of mobile device security, specifically addressing the issue of theft prevention and detection. Mobile theft is a significant concern globally, and this project aims to develop an effective anti-theft solution using Android Studio.

The primary aim of this project is to create a mobile application that can detect potential theft scenarios such as motion, charger disconnection, earphone removal, proximity changes, and SIM card changes. These detections will trigger alarms to notify users and deter theft. The project's repository will house the source code, documentation, and resources related to the development and implementation of the anti-theft application.

The development environment for this project is centered around Android Studio, a widely used integrated development environment (IDE) for Android app development. Android Studio provides a robust platform with essential tools for designing, coding, testing, and debugging Android applications. The project will leverage key features of Android Studio to implement various anti-theft detection modules efficiently. The development process will follow industry standards and best practices to ensure a reliable and user-friendly application.

## WEBSITE :

The Website have the following functions :

- List of stolen mobiles in different countries
* Mobile brands and Model specification
+ Serval Approaches to Anti-theft System for Mobile Phones

## IMPLEMENTATION STEPS :
1. Install XAMPP
2. Open XAMPP start all the servers
3. Download the [WEB-SRP](WEB-SRP.zip) file from the repository
4. Unzip and Move the downloaded file to the XAMPP **htdocs** folder
5. Run the home.html file from the WEB-SRP folder in the web browser
6. Example : http://localhost/Web-SRP/home.html

## APPLICATION :

The Application have the following functions :

The Mobile Anti-theft System Application which is developed in Android Studio 
It has the feature to detect when your Mobile phone is stolen in serval ways
- Motion Detection
- Charger Disconnection Detection
- Earphone Removal Detection
- Proximity Sensor Monitoring
- SIM Card Change Detection

## HARDWARE REQUIRED :

1. Android Smartphone - To install, test and use the application.
2. Computer - To develop and test the application in Android Studio.

## SOFTWARE REQUIRED :

1. Android Studio - Integrated Development Environment (IDE) for Android app development.
2. Java/Kotlin Programming Language - For coding the Android application.
3. Google Maps API - For integrating location tracking functionalities.
4. Classification and Clustering Tools - scikit-learn library in Python and K-means clustering algorithm from scikit-learn.
5. Version Control - Git for managing source code.
6. External Libraries: Third-party libraries for sensor data processing and image/video capture.
7. Documentation Tools: Markdown for project documentation.

## SYSTEM DESIGN :

![diagram-export-10-05-2024-00_26_49 copy](https://github.com/JagadeeshR14/MobileAnti-theftSystem/assets/139132404/ed988464-7480-4277-a9a1-ca48eb1b6bc0)

There are the other Diagrams like Architecture and more. Click [here](Diagram) to explore.

## IMPLEMENTATION STEPS :

1. Install Android Studio and necessary SDKs.
2. Set up Git repository for version control.
3. Download the [Anti_Theft_App](Anti_Theft_App) and [Sim_change_detection](Sim_change_detection) file and open separately in the Android Studio.
4. Develop algorithms in Java/Kotlin for analyzing accelerometer and gyroscope data to detect motion patterns.
5. Integrate sensor data processing into the Android app.
6. Design intuitive user interface screens for configuring system settings and viewing security alerts.
7. Implement interactive elements for user interaction.
8. Develop features for remote locking, data wiping, and capturing images/video through the mobile app.
9. Implement authentication mechanisms to ensure secure access to remote control features.
10. Configure alarm sounds and visual alerts for theft detection events.
11. To Create a Simulation select a Mobile model and download the resource.
12. Run the application and test the application through the Simulation.

## PYTHON NOTEBOOK :

The Python Notebook have the following functions :
- Classification
- Clustering

## CLASSIFICATION :

1. Dataset : Download the [Dataset](PY_Colab/Dataset) file from the repository.
2. Source Code : Download the [Naive-Bayes_KNN_Classification.ipynb](PY_Colab/Naive-Bayes_KNN_Classification.ipynb) and [SVM_LogisticRegression_Classification.ipynb](PY_Colab/SVM_LogisticRegression_Classification.ipynb)
3. Implementation : Open the source code in the [Google-colab](https://colab.research.google.com) and Upload the dataset in the colab folder and run the code.
4. Colab Link :
+ Naive Bayes & KNN classification - https://colab.research.google.com/drive/1b44BtU-opocioKFNHrDt6M6ZRyFXdAK1?usp=sharing
+ SVM & Logistic Regression Classification - https://colab.research.google.com/drive/1qWz0nw4ZvfOlZ1AJ2sxYpvzjoIb9HxJq?usp=sharing

## CLUSTERING :

1. Dataset : Download the [Dataset](PY_Colab/Dataset) file from the repository.
2. Source Code : Download the [K-Means Clustering.ipynb](PY_Colab/K-Means_Clustering.ipynb) and [Hierarchical-Agglo_Clustering.ipynb](PY_Colab/Hierarchical-Agglo_Clustering.ipynb)
3. Implementation : Open the source code in the [Google-colab](https://colab.research.google.com) and Upload the dataset in the colab folder and run the code.
4. Colab Link :
+ K-Means Clustering - https://colab.research.google.com/drive/1bOyg4-gYxH9qR17oIwu5ikw3TmTtHmL5?usp=sharing
+ Hierarchical-Agglo Clustering - https://colab.research.google.com/drive/1E-NXBZsqgW64MCuMV-Zrq0n3UsxnkOg-?usp=sharing

## RESULT :

1. Detection Accuracy - Measure the accuracy of motion detection and location tracking algorithms through testing.
2. User Satisfaction - Gather feedback from beta testers to evaluate user experience and system effectiveness.
3. Security Enhancements - Analyse security logs to identify system vulnerabilities and implement necessary improvements.
4. Performance Optimization - Measure resource consumption and system responsiveness to optimize performance on various Android devices.

Click [here](Result) to explore all the screenshot Results/Outputs of the Website, Application and Python Notebook.

## CONCLUSION :

The Anti-Theft Detection System for Android Phones embodies a comprehensive approach to enhancing device security and preventing unauthorized access. By leveraging motion detection algorithms, geolocation tracking techniques, and remote control features, the system aims to deter theft attempts effectively while empowering users with control over their device's security. Theoretical validations of the system's capabilities, including accurate detection with minimal false alarms, optimized performance, and continuous improvement through user feedback, reinforce its effectiveness in safeguarding devices and providing users with peace of mind. Through iterative development and adaptation, the system remains responsive to evolving security threats and user requirements, ensuring a robust and reliable solution for protecting Android smartphones against theft and unauthorized access.
