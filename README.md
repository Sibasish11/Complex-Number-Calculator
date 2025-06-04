Complex Number Calculator📱
A web-based complex number calculator with an interactive Argand plane visualization, built using Streamlit and Plotly. This application allows users to perform various operations on complex numbers, visualize them on an Argand diagram, and view calculation history.
Features

Input Formats: Supports both rectangular (a + bi) and polar (r∠θ) input formats for complex numbers.
Operations:
Basic: Addition, subtraction, multiplication, and division.
Advanced: Conjugate, power, root, reciprocal, exponential, natural logarithm, modulus, and argument.
Conversions: Convert between rectangular and polar forms.


Visualization: Interactive Argand plane using Plotly to visualize complex numbers as vectors.
History: Tracks previous calculations for reference during the session.
Dark Theme: Modern, user-friendly interface with a dark theme for better readability.

Installation
To run the application locally, follow these steps:
Prerequisites

Python 3.8+
pip (Python package manager)

Steps

Clone the Repository:
git clone https://github.com/yourusername/complex-number-calculator.git
cd complex-number-calculator


Create a Virtual Environment (recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install Dependencies:
pip install -r requirements.txt


Run the Application:
streamlit run app.py

The application will open in your default web browser at http://localhost:8501.


Requirements
The required Python packages are listed in requirements.txt. Key dependencies include:

streamlit
numpy
plotly

Usage

Input Complex Numbers:

Choose between rectangular (a + bi) or polar (r∠θ) format.
Enter the real/imaginary parts or magnitude/angle for two complex numbers (z₁ and z₂).


Select an Operation:

Choose from basic operations (e.g., addition, subtraction), advanced operations (e.g., conjugate, roots), or conversions.
For advanced operations like power or root, specify the exponent or root order.


Calculate and Visualize:

Click the "Calculate" button to perform the operation.
View the result in both rectangular and polar forms.
The Argand plane will display the input numbers and results as vectors.
Hover over points on the plot to see exact values.


View History:

Previous calculations are displayed in the right sidebar.
Use the "Clear History" button to reset the history.



File Structure

app.py: Main Streamlit application containing the core logic, UI, and visualization code.
utils.py: Placeholder for utility functions (currently empty).
calculator.html: HTML template for a basic static version of the calculator (not integrated with the Streamlit app).
README.md: This file, providing an overview and instructions for the project.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a pull request.

Please ensure your code follows the existing style and includes appropriate tests.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Acknowledgements

Built with Streamlit for the web interface.
Visualizations powered by Plotly.


⭐ Star this repo if you find it useful!📩 Reach out for questions or suggestions via 
www.linkedin.com/in/sibasish-padhihari-537204310
