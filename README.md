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

### The following packages are required for the project and are listed in the s ``requirements.txt`` file/ libraries:

<li>dotenv
<li>os
<li>PIL
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

