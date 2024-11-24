#WeatherWise
WeatherWise is a dynamic weather-based advice system designed for both normal users and farmers. By analyzing weather parameters like humidity, temperature, wind speed, and rainfall, the system provides personalized advice to help users make informed decisions.

#Features
*API Endpoints:
  */predict: Accepts weather data as input (POST request) and returns personalized advice.
  */: A simple GET endpoint to check if the server is live.
*Error Handling: Ensures robustness with proper input validation and error messages.
*Frontend: A user-friendly interface for entering weather data and receiving advice.
*Live Server: Integrated with ngrok to expose the application publicly.
#Technology Stack
*Backend: Python, Flask
*Frontend: HTML, TailwindCSS, JavaScript
*Libraries:
  *Data Analysis: pandas, NumPy
  *Data Visualization: Matplotlib, Seaborn
  *Machine Learning: scikit-learn (K-Nearest Neighbors)
  *Server: ngrok
#Dataset and Model
*Dataset:
  *Approx. 300 KB in size with key features: humidity, temperature, wind speed, rainfall, and advice.
*Model:
  *K-Nearest Neighbors (KNN) used for prediction.
*Preprocessing:
  *One-hot encoding for the "advice" column.
  *Scaling of numerical features using StandardScaler.
