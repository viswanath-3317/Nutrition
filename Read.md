🥗 Advancing Nutrition Science through Gemini AI
A web application that leverages Google's Gemini AI to provide comprehensive nutritional analysis of food items.

📋 Project Overview
This application allows users to input food items and receive detailed nutritional information including macronutrients, micronutrients, and calorie content, all powered by Google's Gemini AI.

✨ Features
AI-Powered Analysis: Uses Google Gemini AI for accurate nutritional information
User-Friendly Interface: Clean Streamlit web interface
Comprehensive Reports: Detailed breakdown of macronutrients and micronutrients
Batch Processing: Analyze multiple food items at once
Downloadable Reports: Export nutritional analysis as text files
🚀 Getting Started
Prerequisites
Python 3.8 or higher
Google Gemini API Key
Installation
Clone the repository or download the project files

Install required dependencies:

pip install -r requirements.txt
Set up your Google API Key:
The API key is already configured in .env file
Or update it with your own key: GOOGLE_API_KEY=your_api_key_here
Running the Application
streamlit run app.py
The application will open in your default web browser at http://localhost:8501

📖 How to Use
Enter Food Items: Type food items in the text area, separated by commas

Example: apple, chicken breast, brown rice, broccoli, salmon
Analyze: Click the "Analyze Nutrition" button

View Results: The AI will generate detailed nutritional information including:

Serving sizes
Calories
Macronutrients (protein, fat, carbohydrates, fiber)
Micronutrients (vitamins and minerals)
Health benefits
Download: Optionally download the report for future reference

🏗️ Project Structure
.
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (API key)
├── .gitignore         # Git ignore file
└── README.md          # Project documentation
🔧 Technical Details
Libraries Used
Streamlit: Web application framework
google-generativeai: Google Gemini AI SDK
python-dotenv: Environment variable management
Application Flow
User Input: Food items collected via text area
Prompt Creation: Input formatted into structured prompt
AI Processing: Prompt sent to Gemini AI model
Results Generation: AI analyzes and returns nutritional data
Display: Results presented in user-friendly format
🔐 Security Note
The .env file contains your API key. In production:

Never commit .env to version control
Use environment variables or secure secret management
The .gitignore file should include .env
📝 License
This project is for educational purposes.

🤝 Contributing
Feel free to fork this project and submit pull requests for improvements.

⚠️ Disclaimer
Nutritional information provided is for educational purposes only. Consult healthcare professionals for personalized dietary advice.