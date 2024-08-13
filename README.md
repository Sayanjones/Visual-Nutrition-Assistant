# Dietary Health Advisor: Generative AI for Food Recognition and Calorie Estimation

### Project Overview
The Visual-Nutrition-Assistant is a Health Management App designed to help users analyze their food intake by uploading images of their meals. The app uses the Google Gemini Pro Vision API to calculate the total calories and provide detailed nutritional information for each food item in the image.

### Environment Setup
To create and activate the environment, follow these steps:

**1. Create a Conda Environment:**
   conda create -p venv python==3.10 -y
<br>
**2. Activate the Environment:**
   conda activate venv/
<br>
**3. Install Required Packages:**
   pip install -r requirements.txt
<br>
**4. Deactivate the Environment:**
   conda deactivate

### The following packages are required for the project and are listed in the ```requirements.txt``` file/ libraries:

<li>dotenv
<li>os
<li>pillow
<li>google-generativeai
<li>streamlit

**API Used:** 
GOOGLE_API_KEY(gemini-pro-vision)

### How to Use the App
Run the Streamlit app.
<br>
Enter a text prompt if desired.
<br>
Upload an image of the food items.
<br>
Click the "Tell me the total calories" button.
<br>
The app will display the total calories and detailed information about each food item.

### Implementation
The Visual-Nutrition-Assistant app is built using Python, Streamlit, and the Google Gemini Pro Vision API. Here’s a breakdown of the implementation:

**Environment Setup:**
The project starts by setting up a virtual environment using Conda and installing all the necessary dependencies listed in the ```requirements.txt``` file.

**API Configuration:**
The Google Gemini Pro Vision API is configured to analyze images and generate content based on the input provided by the user.

**Image Processing:**
The app accepts image uploads from the user, processes the image data, and sends it to the API for analysis.

**User Interface:**
Streamlit is used to create a simple and intuitive user interface where users can input text prompts, upload images, and receive detailed nutritional information about the food items in the image.

**Nutritional Analysis:**
The app sends the image and prompts to the Google Gemini Pro Vision API, which returns a detailed analysis of the food items, including calorie counts.

### Methodology
The methodology behind the Visual Nutrition Assistant is as follows:

**Data Input:** Users provide input by uploading an image of their meal and optionally entering a text prompt to guide the analysis.
<br>
**Image Processing:** The uploaded image is processed and prepared for analysis. This involves converting the image into a format suitable for the API.
<br>
**Content Generation:** The processed image and prompt are sent to the Google Gemini Pro Vision API, which uses advanced AI models to analyze the food items in the image.
<br>
**Nutritional Calculation:** The API generates a response that includes a list of food items, along with their respective calorie counts and other nutritional information.
<br>
**Output Display:** The results are displayed to the user in a clear and organized format, allowing them to easily understand the nutritional content of their meal.

### Conclusion:
The Visual Nutrition Assistant successfully provides users with an easy and effective way to analyze the nutritional content of their meals. By leveraging the power of Google’s Gemini Pro Vision API and a user-friendly Streamlit interface, the app offers a practical solution for those looking to maintain a healthy diet. This project demonstrates the potential of AI and machine learning in the field of health management, making it easier for users to make informed dietary choices.

### Future Scope:
There are several potential areas for the future development of the visual nutrition assistant:

**Expanded Food Database:**Integrate with larger and more diverse food databases to provide even more accurate and comprehensive nutritional information.
<br>
**Multi-Language Support:** Add support for multiple languages to make the app accessible to a global audience.
<br>
**Enhanced AI Models:** Utilize more advanced AI models to improve the accuracy of food item recognition and nutritional analysis.
<br>
**Mobile Application:** Develop a mobile version of the app for greater accessibility and convenience.
<br>
**Dietary Recommendations:** Include personalized dietary recommendations based on the user’s health goals and preferences.
<br>
**User Data Integration:** Allow users to save and track their nutritional data over time, providing insights into their eating habits and progress toward health goals.

