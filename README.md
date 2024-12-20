# Harry Potter Sorting Hat <img src="https://github.com/Samarth-Khatri/Sorting-Hat/blob/main/images/Hog.png" width="30px">

Welcome to the **Harry Potter Sorting Hat** project! This machine learning-based web application classifies users into one of the four Hogwarts Houses based on their personality traits derived from the Big Five Personality Score.

Hogwarts was founded over a thousand years ago by four powerful wizards: Godric Gryffindor, Salazar Slytherin, Rowena Ravenclaw, and Helga Hufflepuff. They chose to split the students into four ‘houses’, each bearing their surnames and featuring young wizards and witches who displayed abilities and personalities they wanted to nurture.

To do this, Godric Gryffindor used his magical hat – henceforward known as the Sorting Hat – to decide which children should go into which house, and so it has been ever since with a yearly Sorting Ceremony that places each new pupil into their own new home.

The four houses have different entry requirements, and nobody summed them up better than the old Sorting Hat itself in its welcoming song:

### Gryffindor <img src="https://github.com/Samarth-Khatri/Sorting-Hat/blob/main/images/G.png" width="20px">
‘You might belong in Gryffindor,  
Where dwell the brave at heart,  
Their daring, nerve and chivalry  
Set Gryffindors apart.’

### Hufflepuff <img src="https://github.com/Samarth-Khatri/Sorting-Hat/blob/main/images/H.png" width="20px">
‘You might belong in Hufflepuff  
Where they are just and loyal  
Those patient Hufflepuffs are true  
And unafraid of toil.’

### Ravenclaw <img src="https://github.com/Samarth-Khatri/Sorting-Hat/blob/main/images/R.png" width="20px">
‘Or yet in wise old Ravenclaw  
If you’ve a ready mind  
Where those of wit and learning  
Will always find their kind.’

### Slytherin <img src="https://github.com/Samarth-Khatri/Sorting-Hat/blob/main/images/S.png" width="20px">
‘Or perhaps in Slytherin  
You’ll make your real friends  
Those cunning folk use any means  
To achieve their ends.’

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Model Details](#model-details)
- [Screenshots and Video](#screenshots-and-video)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

This project uses a machine learning model to predict a user’s Hogwarts House: Gryffindor, Hufflepuff, Ravenclaw, or Slytherin. The classification is based on the Big Five Personality Score, which measures personality traits such as openness, conscientiousness, extraversion, agreeableness, and neuroticism.

---

## Features

- Interactive web application to predict Hogwarts House
- Dynamic UI for personality trait input
- Integration of a trained ML model with Flask backend
- Accurate predictions with 81.34% accuracy on test data

---

## Tech Stack

### Frontend
- **HTML**
- **CSS**
- **JavaScript**
- **Bootstrap**

### Backend
- **Python**
- **Flask**

### Machine Learning
- **scikit-learn**
- **pandas**
- **numpy**

---

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Angad-2002/Harry-Potter-Sorting-Hat.git
    cd Harry-Potter-Sorting-Hat
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    # For Windows:
    venv\Scripts\activate
    # For macOS/Linux:
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Flask application:
    ```bash
    python app.py
    ```

5. Open your browser and go to:
    ```
    http://127.0.0.1:5000/
    ```

---

## Usage

1. Input your Big Five Personality traits into the form on the web application.
2. Submit the form to get your Hogwarts House prediction.
3. View your house along with a brief description of its qualities.

---

## Dataset

The project uses a preprocessed dataset containing individuals’ Big Five Personality Scores and their associated Hogwarts Houses. The dataset was cleaned and split into training and testing sets for model evaluation.

### Box Chart Representation

The dataset was created based on the personality traits visualized in the following box chart:

![Box Chart of Personality Traits](image.png)

The chart represents the distribution of traits such as Agreeableness, Conscientiousness, Emotional Stability, Extraversion, and Intellect for individuals grouped by their Hogwarts Houses.

---

## Results

- **Model Accuracy**: 81.34% on the test dataset.
- **Classifier**: Trained using scikit-learn's machine learning algorithms.

---

## Model Details

The project employs the **Gaussian Naive Bayes Classifier** to classify individuals into Hogwarts Houses. Key highlights of the model:

- **Algorithm**: Gaussian Naive Bayes
  - Assumes that features follow a Gaussian (Normal) distribution.
  - Suitable for continuous input features like personality trait scores.
  - Simple and computationally efficient.

- **Why Gaussian Naive Bayes?**
  - Works well with smaller datasets.
  - Handles continuous data effectively by modeling feature likelihoods with Gaussian distribution.
  - Provides fast predictions, ideal for a real-time application like this.

---

## Screenshots and Video

### Screenshots
1. **Homepage**  
   ![Screenshot 2024-12-20 214311](https://github.com/user-attachments/assets/ebde5d9b-301f-4475-9c11-7cbe11df5dfe)

2. **Personality Input Page**  
   ![Screenshot 2024-12-20 214321](https://github.com/user-attachments/assets/3246f842-eb4e-49ed-89a6-f6cf6a1d0d6b)

3. **Prediction Results Page**  
   ![image](https://github.com/user-attachments/assets/21b50605-7637-49ba-86fb-339c22c8d76a)

### Video Demo
Watch the application in action:
[![Watch the Video Demo](https://img.youtube.com/vi/qdcVZqIlih8/maxresdefault.jpg)](https://youtu.be/qdcVZqIlih8)
> *Click the thumbnail to watch the video on YouTube.*

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to:

1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```bash
    git push origin feature-name
    ```
5. Open a Pull Request.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For any inquiries, feel free to reach out:

- **Author**: Angad Singh  
- **Email**: angadsingh.11.09.2002@gmail.com  
- **GitHub**: [Angad-2002](https://github.com/Angad-2002)
