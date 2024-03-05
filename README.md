## Prerequisites

Before running the application, make sure you have the following prerequisites:

- Python 3.10 and above installed
- [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) installed
- Pip installed
- Create a `.env` file in the project directory with the following content:

  ```env
  GOOGLE_API_KEY="<your_api_key>"
  Replace the placeholder "your_api_key" with your actual Google API key.
  To create your own API key visit : "https://aistudio.google.com/app/apikey"

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/dushyantsinghpawar/Gemini_API_Image_to_Calorie_Calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Gemini_API_Image_to_Calorie_Calculator
   ```

3. Create and activate a virtual environment using conda:

   ```bash
   conda create --name gemini-health-app python=3.10
   conda activate gemini-health-app
   ```

   Replace `3.10` with your desired Python version.

4. Install dependencies:

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

image_test_<> are images used for testing the app.
