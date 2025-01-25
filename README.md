# 🏥 Health Care Chatbot

A healthcare chatbot designed to assist users in diagnosing potential diseases based on their symptoms. By utilizing machine learning techniques, specifically a *Decision Tree Classifier*, the chatbot predicts possible health conditions and suggests relevant medical professionals for consultation. The goal is to provide an accessible tool for preliminary health assessments and guide users toward appropriate medical attention.

---

## 📄 Table of Contents

1. [Overview](#-overview)
2. [Key Features](#-key-features)
3. [Technologies Used](#-technologies-used)
4. [Challenges Faced](#-challenges-faced)
5. [Future Enhancements](#-future-enhancements)
6. [Contributing](#-contributing)


---

## 👥 Meet the Team

This project was developed by

- [Argha Bandyopadhyay](https://www.linkedin.com/in/argha-bandyopadhyay-a856b5292/) 🌟


---

## 📝 Overview

This project is a *Health Care Chatbot* that assists users in conducting preliminary health assessments based on their symptoms. Using a *Decision Tree Classifier* for symptom classification, the chatbot provides possible diagnoses along with confidence levels and doctor recommendations via a user-friendly graphical interface built using *Tkinter*. 

The key objectives are:
- Symptom-based disease diagnosis
- Guiding users towards medical attention
- Simplifying access to doctors through dynamic hyperlinks

---

## ✨ Key Features

- *Symptom-based Diagnosis: Using a **Decision Tree Classifier*, the chatbot predicts possible diseases based on the user's symptoms.
- *Confidence Level Assessment*: The chatbot calculates a confidence level based on the number of matching symptoms.
- *Doctor Recommendation*: Suggests doctors for consultation, with hyperlinks for easy access to their profiles.
- *User-friendly GUI: Built with **Tkinter*, the chatbot features an intuitive graphical interface for easy interaction.

---

## 🛠 Technologies Used

- *Machine Learning*: Decision Tree Classifier from scikit-learn for disease prediction.
- *Tkinter*: For creating a clean and interactive graphical user interface.
- *Pandas* and *NumPy*: For efficient data manipulation and symptom processing.
- *Web Scraping*: To dynamically fetch doctor consultation links.
- *Python Libraries*:
  - scikit-learn: For machine learning model training.
  - LabelEncoder: For encoding categorical features.
  - webbrowser: To open hyperlinks for external doctor consultations.

---

## ⚙ Challenges Faced

1. *Symptom Classification: Managing a large number of symptoms and ensuring efficient classification was a major challenge. By applying **dimensionality reduction techniques*, redundant features were removed, which improved both the performance and speed of the model.
   
2. *User Interaction Flow: Ensuring a smooth interaction between the user and chatbot posed UI design challenges. This was overcome by creating an intuitive design using **Tkinter*, where users can easily navigate through a series of questions with well-placed buttons and text boxes.

3. *Hyperlink Integration: Integrating dynamic hyperlinks for doctor recommendations required combining web functionality with the GUI. This was achieved by using the **HyperlinkManager* class to seamlessly open doctor profiles in the browser.

---

## 🚀 Future Enhancements

- *Advanced Diagnosis: Implement more sophisticated machine learning models such as **Random Forests* or *Neural Networks* to improve diagnostic accuracy.
- *Voice Integration*: Add voice recognition for symptom entry to enhance user accessibility.
- *Mobile Application*: Develop a mobile-friendly version of the chatbot, allowing users to access it on the go.
- *Data Updates*: Continuously update the medical dataset to ensure that diagnoses and doctor recommendations stay relevant.

---

## 🤝 Contributing

We welcome contributions from developers of all skill levels! Here’s how you can contribute:

1. *Fork the repository*.
2. *Create a branch* (git checkout -b feature-branch).
3. *Commit your changes* (git commit -m 'Add a new feature').
4. *Push to the branch* (git push origin feature-branch).
5. *Open a Pull Request* and explain your changes.
