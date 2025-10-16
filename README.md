# Registration Chatbot

A web-based chatbot for registration purposes. This chatbot guides users step by step through a registration process and can export all collected data as a JSON file.

![Chatbot Screenshot](https://github.com/user-attachments/assets/a8cab3d0-5501-4a18-8529-9d6e8a4945a4)

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
  - Payment details (cardholder name and card info)

- **Validation**  
  Some fields, like phone number, email, ZIP code, and OTP, are validated to ensure proper input.

- **Export data**  
  After completing the registration, all collected data can be exported to a JSON file for easy storage and processing.

- **Interactive interface**  
  Uses buttons and input fields to guide the user through the registration steps.

## How it Works

1. User starts the chatbot and answers questions in sequence.  
2. User input is validated based on type and format.  
3. Program and gear options are fetched dynamically from APIs.  
4. Users can select multiple gear items with attributes.  
5. At the end, all answers are compiled into a JSON object.  
6. User can export the JSON data using the "Export JSON" button.

## Usage

1. Open `RegistrationChatBot.html` in a modern web browser.  
2. Follow the prompts in the chatbot interface.  
3. Click **Export JSON** at the end to download the registration data.

## Technologies Used

- HTML
- CSS
- JavaScript (Vanilla)
- Fetch API for dynamic data

## License

MIT License
