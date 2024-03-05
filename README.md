# Gemini_API_Image_to_Calorie_Calculator

Gemini Health App is a web application that leverages the Google GenerativeAI (Gemini Pro API) to process images of food, calculate total calories, and assess the healthiness of the detected food items.

## Prerequisites

Before running the application, make sure you have the following prerequisites:

- Python 3.x installed
- Pip installed
- Create a `.env` file in the project directory with the following content:

  ```env
  GOOGLE_API_KEY="<your_api_key>"
  ```

  Replace the placeholder `<your_api_key>` with your actual Google API key.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Gemini_API_Image_to_Calorie_Calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Gemini_API_Image_to_Calorie_Calculator
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Set up your Google API key by creating a `.env` file in the project root directory.

2. Run the application:

   ```bash
   streamlit run app.py
   ```

3. Open your web browser and visit `http://localhost:8501` to access the Gemini Health App.

4. Upload an image, and click the "Tell me about the total calories in my food" button to receive information about the total calories and healthiness of the detected food items.

5. Images folder contain images used for testing the app.

## Contributing

If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Make your changes.
4. Create a pull request.

## Acknowledgments

- Thanks to the Google GenerativeAI team for providing the powerful Gemini Pro API.

```

Remember to replace placeholders such as `your-username` in the clone URL with your actual GitHub username. This README provides information on setting up the project, installing dependencies, using the application, and contributing to the repository.
