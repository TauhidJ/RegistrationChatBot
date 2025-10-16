# Registration Chatbot

A web-based chatbot for registration purposes. This chatbot guides users step by step through a registration process and can export all collected data as a JSON file.

<img width="413" height="807" alt="image" src="https://github.com/user-attachments/assets/6f633631-4bb3-452a-8fbc-3bf708ae8ff1" />

## Live Demo

Try the chatbot online here: [https://tauhidj.github.io/RegistrationChatBot/](https://tauhidj.github.io/RegistrationChatBot/)

## Features

- **Step-by-step registration**  
  The chatbot asks a series of questions to collect necessary details:
  - Phone number (with validation)
  - Email (with validation)
  - OTP verification for phone and email
  - Guardian information (first name, last name, address, ZIP code)
  - Player information (first name, last name, date of birth, gender, school)
  - Program selection (Classes or Leagues)
  - Program-specific selections
  - Optional gear selection with attributes like size and color
  - Multiple gear selection support
  - Payment details (cardholder name and card info)

- **Validation**  
  Some fields, like phone number, email, ZIP code, and OTP, are validated to ensure proper input.

- **Export data**  
  After completing the registration, all collected data can be exported to a JSON file for easy storage and processing.

- **Interactive mobile-style interface**  
  The chatbot UI is fixed to a **mobile view layout** for a realistic chatbot experience on both desktop and mobile browsers.

## How it Works

1. User starts the chatbot and answers questions in sequence.  
2. User input is validated based on type and format.  
3. Program and gear options are fetched dynamically from APIs.  
4. Users can select **multiple gear items** with attributes (size and color).  
5. At the end, all answers are compiled into a JSON object.  
6. User can export the JSON data using the "Export JSON" button.

## Usage

1. Open `RegistrationChatBot.html` in a modern web browser **or** use the [live demo](https://tauhidj.github.io/RegistrationChatBot/).  
2. Follow the prompts in the chatbot interface.  
3. Click **Export JSON** at the end to download the registration data.

## Technologies Used

- HTML  
- CSS  
- JavaScript (Vanilla)  
- Fetch API for dynamic data

## License

MIT License
