# **Python Weather Dashboard**

## **Overview of the Project**

This is a desktop graphical user interface (GUI) application built with Python that fetches current weather data for a specified city. It uses the OpenWeatherMap API to retrieve real-time information including temperature, humidity, wind speed, and weather conditions. The application features a modern, full-screen dashboard design using Tkinter and dynamically changes the background image to match current weather condition (e.g., sunny, rainy, cloudy).

## **Features**

* **Real-time Weather Data:** Fetches current weather statistics using the OpenWeatherMap API.  
* **Modern GUI:** A clean, card-style interface built using Tkinter and themed ttk widgets.  
* **Full-Screen Display:** The application launches in full-screen mode for an immersive experience.  
* **Dynamic Backgrounds:** The background image changes automatically based on the fetched weather condition code (e.g., displaying a rainy image for rain, sunny for clear skies).  
* **Robust Error Handling:** Includes user-friendly pop-up error messages for invalid city names, network connection issues, or API errors.  
* **Metric Units:** Displays temperature in Celsius (°C) and wind speed in km/h.

## **Technologies/Tools Used**

* **Programming Language:** Python 3.x  
* **GUI Libraries:**  
  * tkinter (Standard Python interface to the Tk GUI toolkit)  
  * tkinter.ttk (Themed widgets)  
  * tkinter.messagebox (For error pop-ups)  
  * tkinter.simpledialog (For user input prompts)  
* **External Libraries:**  
  * requests (For making HTTP HTTP requests to the weather API)  
  * Pillow (PIL fork \- used for loading and resizing background images)  
* **API Service:** OpenWeatherMap (Current Weather Data)

## **Steps to Install & Run the Project**

### **Prerequisites**

Ensure you have Python installed on your system. You will also need an active internet connection.

### **1\. Clone or Download the Repository**

Download the Python script (e.g., weather\_app.py) and place it in a project folder.

### **2\. Install Dependencies**

Open your terminal or command prompt, navigate to the project folder, and install the required external Python libraries using pip:

pip install requests Pillow

### **3\. Prepare Image Assets**

For the dynamic background feature to work, you must have the following image files in the **same directory** as your Python script:

* sunny.jpg  
* rainy.jpg  
* cloudy.jpg  
* pcloudy.jpg (for partly cloudy)  
* Thunderstorm.jpg  
* Dizzle.jpg  
* default.jpg (used as a fallback)

*(Note: If these images are missing, the application will still run but will display a warning in the console and lack a background image.)*

### **4\. Configure API Key**

The script requires an OpenWeatherMap API key.

1. Open the Python script in a text editor.  
2. Locate the line: API\_KEY \= "bb9df5083ba5dc0d4690631d62c78185"  
3. Ideally, replace the existing key with your own valid API key obtained from [OpenWeatherMap](https://openweathermap.org/api).

### **5\. Run the Project**

Open the terminal to the CODE file location then Execute the given command

python CODE.py

## **Instructions for Testing**

1. Upon running the script, a dialog box titled "Weather Application" will appear prompting for input.  
2. Enter the name of a known city (e.g., "London", "Mumbai", "Tokyo") and click OK.  
3. The application will launch into full screen, displaying the weather details for that city. The background image should reflect the reported weather condition.  
4. To test error handling, rerun the script and enter an invalid city name (e.g., "InvalidCityName"). A pop-up error message should appear saying "City not found".  
5. To close the application, you will need to use your system's standard method for exiting full-screen applications (e.g., Alt+F4 or moving the mouse to the top of the screen to reveal window controls).

## **Screenshots**
![](image/Screenshot%202025-11-22%20214931.png)
![](image/Screenshot%202025-11-22%20215139.png)
![](image//Screenshot%202025-11-22%20215245.png)
![](image/Screenshot%202025-11-22%20215432.png)
![](image/Screenshot%202025-11-23%20112130.png)
