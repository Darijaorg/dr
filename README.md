
# Darija-database2024

Darija-database2024 is a web application that allows users to store and display Moroccan Darija words with their English translations and additional details. The project uses Firebase Realtime Database to manage and persist data.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project provides a simple interface to manage a database of Moroccan Darija words. Users can add new words, view existing ones, and categorize them by type (verbs, nouns, adjectives, and pronouns). The application is built using HTML, CSS, JavaScript, and Firebase.

## Features
- **Add New Words**: Users can input new Darija words along with their English translation, type (e.g., verb, noun, adjective), and optional details.
- **View Words**: The application displays stored words categorized by type.
- **Firebase Integration**: Real-time storage and retrieval of words using Firebase Realtime Database.

## Technologies
- **HTML/CSS**: Structure and styling of the web pages.
- **JavaScript**: Logic for interacting with Firebase and handling user inputs.
- **Firebase**: Realtime Database for storing and retrieving words.
- **Font Awesome**: Icons used in the interface.

## Setup
To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abdelhakim-sahifa/darija-database2024.git
   cd darija-database2024
   ```

2. **Open `index.html` in your web browser:**
   ```bash
   open index.html
   ```

3. **Ensure internet connection**: The project relies on external libraries (Firebase, Font Awesome) loaded via CDN.

## Usage
- **Homepage**: The main page (`index.html`) provides navigation to add new words or view existing words.
- **Add New Word**: Use `entreNewWord.html` to input a new word, translation, type, and details.
- **View Words**: Visit `darijaWords.html` to see all stored words categorized by type.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

