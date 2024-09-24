
# AI-powered Personalized Health Advisor

This project is a web-based AI-powered Personalized Health Advisor built with Python and Flask. It allows users to input their daily health metrics, such as calories burned and water intake, over multiple days, and then generates visualizations to help users track their health progress. 

The project uses **Flask** for the web framework, **Matplotlib** for generating health metric plots, and **Bootstrap** for a clean and responsive user interface.

## Features

- **User Data Input**: Users can input their health data (calories burned and water intake) for multiple days.
- **Health Visualization**: After submitting the data, the app generates a plot of the user's health metrics.
- **Responsive UI**: The interface is styled using Bootstrap for a modern, mobile-friendly design.
- **Data Logging**: You can extend this project to store user inputs and provide personalized recommendations.

## Technologies Used

- **Python** (Flask, Matplotlib)
- **HTML** & **CSS**
- **Bootstrap 5** (for responsive design)
- **JavaScript** (for dynamic form fields)

## Getting Started

### Prerequisites

Make sure you have **Python** and **pip** installed on your machine. 

To install Python, go to [Python's official website](https://www.python.org/downloads/).

### Setup Instructions

1. **Clone the repository** (if you’re using GitHub):
   ```bash
   git clone https://github.com/your-repository/personalized-health-advisor.git
   cd personalized-health-advisor
   ```

2. **Set up a virtual environment** (recommended):
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**:

   - On **Windows**:
     ```bash
     .\venv\Scripts\activate
     ```

   - On **macOS/Linux**:
     ```bash
     source venv/bin/activate
     ```

4. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

   If the `requirements.txt` file does not exist, you can manually install the key libraries:
   
   ```bash
   pip install Flask matplotlib
   ```

### Running the App

1. **Start the Flask application**:
   ```bash
   python app.py
   ```

2. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

### Project Structure

```
AI project health/
│
├── app.py                # Main Flask application
├── templates/            # HTML files
│   ├── index.html        # Input form
│   └── result.html       # Plot display
├── static/
│   └── css/
│       └── styles.css    # Custom CSS file
└── .venv/                # Virtual environment directory (optional)
```

### Key Files:

- **app.py**: The main Flask app that handles routing, data processing, and plot generation.
- **index.html**: The form for inputting health data.
- **result.html**: The page that displays the plot.
- **styles.css**: Custom CSS for additional styling (optional).
- **requirements.txt**: Lists all the Python dependencies for the project.

### Usage

1. Navigate to the app’s homepage (`http://127.0.0.1:5000/`) and input the number of days for which you want to enter health data.
2. Enter daily metrics for each day (calories burned, water intake).
3. Submit the form, and the app will generate a visualization of your health metrics over the specified days.

### Example

- **Home Page (Input Form)**:
  ![Input Form](example-input.png)

- **Generated Health Plot**:
  ![Generated Plot](example-plot.png)

### Future Improvements

- **User Authentication**: Allow users to log in and track their progress over time.
- **Database Integration**: Store user inputs in a database to enable historical data tracking.
- **Personalized Recommendations**: Use machine learning models to offer personalized health advice based on user data.

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

```

