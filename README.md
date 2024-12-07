# **Visual Nutrition Assistant: Gen AI for Food Recognition and Calorie Estimation**

## **Project Overview**  
The **Visual-Nutrition-Assistant** is a Health Management App that empowers users to make informed dietary choices. By analyzing images of meals using the **Google Gemini Pro Vision API**, the app provides detailed nutritional information, including total calorie counts for each food item.  

---

## **Environment Setup**  

### **Steps to Create and Activate the Environment**  
1. **Create a Conda Environment**  
   ```bash
   conda create -p venv python==3.10 -y
   ```
2. **Activate the Environment**  
   ```bash
   conda activate venv/
   ```
3. **Install Required Packages**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Deactivate the Environment**  
   ```bash
   conda deactivate
   ```  

---

## **Dependencies**  
The required packages are specified in the `requirements.txt` file. Key dependencies include:  
- `dotenv`  
- `os`  
- `pillow`  
- `google-generativeai`  
- `streamlit`  

### **API Used**  
- **Google Gemini Pro Vision API**  
  - API Key: `GOOGLE_API_KEY`

---

## **How to Use the App**  
1. Run the Streamlit app:  
   ```bash
   streamlit run app.py
   ```  
2. Provide an optional text prompt.  
3. Upload an image of your meal.  
4. Click the **"Tell me the total calories"** button.  
5. View the detailed nutritional breakdown and total calorie count.  

---

## **Implementation**  
### **1. Environment Setup**  
The project uses Conda to manage the virtual environment and ensure all dependencies are installed.  

### **2. API Configuration**  
The **Google Gemini Pro Vision API** is configured to analyze meal images and generate nutritional data.  

### **3. Image Processing**  
The app processes uploaded images into a format suitable for the API and extracts relevant features for analysis.  

### **4. User Interface**  
A simple and intuitive interface built with Streamlit enables users to upload images, enter prompts, and visualize results.  

### **5. Nutritional Analysis**  
The app leverages advanced AI models to extract detailed insights, such as calorie counts and nutritional values for each food item.

---

## **Methodology**  
1. **Data Input**  
   - Users upload meal images and optionally provide a text prompt for guided analysis.  

2. **Image Processing**  
   - Images are preprocessed for compatibility with the API.  

3. **Content Generation**  
   - Processed inputs are sent to the **Google Gemini Pro Vision API** for detailed analysis.  

4. **Nutritional Calculation**  
   - The API response includes food item recognition and calorie/nutritional values.  

5. **Output Display**  
   - Results are displayed in an organized and user-friendly format.  

---

## **Future Scope**  
1. **Expanded Food Database**  
   - Enhance the app's accuracy by integrating comprehensive food databases.  

2. **Multi-Language Support**  
   - Support multiple languages for a wider audience reach.  

3. **Improved AI Models**  
   - Incorporate advanced AI models for better accuracy in food recognition and analysis.  

4. **Mobile Application**  
   - Develop a mobile version for easier accessibility.  

5. **Dietary Recommendations**  
   - Provide personalized dietary suggestions tailored to user preferences and goals.  

6. **User Data Integration**  
   - Enable tracking of user nutritional data to offer insights into eating habits and progress.  

---

## **Conclusion**  
The **Visual Nutrition Assistant** bridges the gap between advanced AI and practical health management. By leveraging the **Google Gemini Pro Vision API** and a seamless Streamlit interface, the app equips users with insights to make healthier dietary choices.  

---

This documentation is concise, comprehensive, and user-friendly, ensuring that collaborators and users can easily understand and contribute to the project. 

---

Happy Coding :)
