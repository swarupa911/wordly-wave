# Project Title: Wordwave - Text Trender Application

---

## Project Details:
- **Project Demo URL:** [Wordwave Demo](https://wordwave.proudstone-87fbc107.centralindia.azurecontainerapps.io/)
- **Demo Video URL:** [Wordwave Demo Video](https://drive.google.com/file/d/14-Y9TDa_NExllcyRvRRCiDoO8Pcvryf9/view?usp=drive_link)
- **GitHub Repository URL:** [Wordwave GitHub Repository](https://github.com/swarupa911/wordly-wave)
- **Industry:** Technology

---

## Project Overview:
Wordwave is a text processing application designed to provide functionalities such as word counting, character counting, text-to-speech conversion, font style management, and text correction. The application is built with a user-friendly interface that allows users to perform various text manipulations efficiently. Wordwave is deployed on Azure, utilizing Azure Container Apps for scalability and reliability.

---

## Technologies Used:
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js (Express)
- **Cloud Services:**
  - **Azure Blob Storage:** For storing any generated content securely.
  - **Azure Container Apps:** For deploying the application in a scalable environment.
  - **Azure Container Registry (ACR):** For managing container images used in the deployment process.
- **Other Libraries:**
  - **Speech Synthesis API:** Converts text to voice notes.
  - **Multer:** For handling file uploads if required.
  - **Grammar and Spell Check Libraries:** Integrated for text correction features.

---

## Key Features:

### **Text Analysis Tools:**
- **Word and Character Counter:** Quickly counts the number of words and characters in the text provided by the user.
- **Syllable Counter:** Helps in calculating the number of syllables in the text for linguistic analysis.

### **Text-to-Voice Conversion:**
- Converts input text into a voice note using the Speech Synthesis API. Users can choose from different voices and adjust the speed to suit their needs.

### **Font Style and Formatting Options:**
- Users can change the font style of their text, providing flexibility in text presentation for various purposes, such as reports and documents.

### **Text Correction and Formatting:**
- Offers features to remove extra spaces and perform text corrections, enhancing the readability and quality of the text.

### **Dark Mode:**
- A toggle for enabling dark mode, providing a better user experience in low-light conditions.

### **Export and Share:**
- Users can export the processed text or voice notes into various formats like PDF or MP3 for easy sharing and use.

---

## Deployment Information:

### **Cloud Services:**
- **Azure Container Apps:** Deployed on Azure Container Apps for a scalable, managed serverless environment that auto-scales based on traffic and resource needs.
- **Azure Blob Storage:** Manages files and voice notes generated or uploaded by users.
- **Azure Container Registry (ACR):** Hosts and manages the container images required for the deployment of the Wordwave application.

### **Deployment Process:**
1. **Building Docker Image:** The application is containerized using Docker, and the image is built and pushed to **Azure Container Registry**.
2. **Deploying with Azure Container Apps:** The containerized application is deployed using **Azure Container Apps**, ensuring easy scaling and integration with other Azure services.

---

## Future Enhancements:

### **Enhanced Text Analysis:**
- Integrate advanced text analytics features such as sentiment analysis and keyword extraction.

### **More Language and Voice Options:**
- Expand the text-to-speech capabilities to support more languages and provide more voice options.

### **User Authentication and Personalization:**
- Implement user authentication to save user preferences and provide a personalized experience.

### **File Management Enhancements:**
- Introduce features to manage and categorize exported files more efficiently.

---
