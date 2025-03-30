# VisionCalc
VisionCalc is a web application that enables users to draw mathematical expressions containing numbers (0-9), operators (+, -, *, /), and square brackets ([, ]). Using a CNN-based machine learning model, the system recognizes handwritten characters, converts them into a valid mathematical expression, and evaluates the result in real time.

# Team Members:
Sanjayazhagan
Gokul Krishna Balaji
Neppali Puneeth Kumar

# Solution Overview
1️. User draws a mathematical expression (e.g., "12 + [4 * 3]") on the canvas.
2️. Image is preprocessed (converted to grayscale).
3️. Image is sent to the Flask backend, where the Machine Learning model (Random Forest) predicts individual characters.
4️. Predicted characters are converted into a valid mathematical expression (e.g., 12 + [4 * 3]).
5️. The expression is evaluated, and the result is computed.
6️. The final result is sent back to the frontend and displayed to the user.
