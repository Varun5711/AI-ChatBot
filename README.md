# Quantum AI

Quantum AI is a conversational AI project designed to provide intelligent and interactive chat experiences. The application allows users to send messages, upload files, and receive responses powered by the Gemini 1.5 Flash API. This document provides an overview of the project, its features, setup instructions, and usage guidelines.

---

## Features

1. **Interactive Chat Interface**
   - Users can send text messages to the AI and receive responses with typing effects for an engaging experience.
   
2. **File Upload**
   - Support for uploading files to include as part of the chat interaction.

3. **Dynamic AI Responses**
   - AI generates responses using the Gemini 1.5 Flash API, ensuring relevant and accurate replies.

4. **Responsive Design**
   - Optimized for both desktop and mobile devices, ensuring usability across various screen sizes.

5. **Typing Effect**
   - Simulates a typing animation for AI responses to enhance user experience.

6. **Navbar with Toggle**
   - A responsive navigation bar with a hamburger menu for improved accessibility.

---

## Setup Instructions

### Prerequisites
- A modern web browser
- An API key for the Gemini 1.5 Flash API

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/quantum-ai.git
   ```
2. Navigate to the project directory:
   ```bash
   cd quantum-ai
   ```
3. Open the `index.html` file in your browser to view the application.

### Configuration
1. Replace the `Api_Url` variable in the script with your Gemini 1.5 Flash API key:
   ```javascript
   const Api_Url = "https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key=YOUR_API_KEY";
   ```

---

## Usage

1. **Sending Messages**
   - Type a message in the input field and press `Enter` or click the submit button.

2. **Uploading Files**
   - Click the image icon to upload a file.
   - Supported file types are displayed in the chat for context.

3. **Viewing Responses**
   - AI responses will appear with a typing effect and smooth scrolling to the latest message.

4. **Toggle Navigation**
   - Use the hamburger icon to expand or collapse the navigation links.

---

## Dependencies

- **Gemini 1.5 Flash API**: For generating intelligent responses.
- **Typed.js**: Provides the typing effect for the chat messages.

---

## Project Structure

- **index.html**: Main HTML file.
- **script.js**: Contains JavaScript logic for chat interaction and API integration.
- **styles.css**: Defines styles for the application.
- **assets/**: Contains images and other static resources.

---

## Contribution

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature description"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

For questions or feedback, please reach out:
- **Email**: varunhotani@gmail.com
- **GitHub**: [Varun5711](https://github.com/Varun5711)
- **LinkedIn**: [Varun Hotani](https://www.linkedin.com/in/varun-hotani-51b046300/)

---

## Acknowledgments

- The Gemini 1.5 Flash API team for their powerful language model.
- Typed.js contributors for the typing effect library.

---

Thank you for using Quantum AI!

