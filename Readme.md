# Resume and Personality Assessment Web App

This project is a web application built with Flask and Streamlit combined that assesses Resume and personality based on user responses to a set of questions. The application presents questions to the user, collects their responses, and generates a personality chart based on their answers.

## Features

- Detailed Resume analysis .
- Tips and Trick based on your resume.
- User-friendly interface for answering personality assessment questions.
- Data visualization using Chart.js to display personality traits.
- Backend processing of user responses to generate personality insights.
- Integration with two K-means clustering models stored in the `models` directory for personality analysis.

## Files and Folders
- **App.py**: Streamlit app for Resume analysis using pyresparser and other important modules.
- **Flask_app.py**: Flask application file that defines routes and handles user interactions.
- **Test.py**: Python script containing functions for generating personality charts based on user responses.
- **questions.csv**: CSV file containing the questions for the personality assessment.
- **css/**: Folder containing CSS files for styling the web interface.
- **templates/**: Folder containing HTML templates for rendering the web pages.
- **models/**: Folder containing two K-means clustering models used for personality analysis.

## Installation and Setup

1. Clone the repository:

    ```
    git clone https://github.com/pravincoder/personality_app.git
    ```

2. Download and install XAMPP for database and Click on 'Start' for Apache and MySql.

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```
    
5.(Start a new Terminal '+') Run the Flask application:
    
    ```
    python flask_app.py
    ```
    
6. Access the streamlit application in your web browser at `http://localhost:8501`.

## Sample Output Img

![ScreenShot of Resume analysis 1](https://github.com/pravincoder/Skills-Personality_Insights/output_img/ss1.png)

![ScreenShot of Resume analysis 2](https://github.com/pravincoder/Skills-Personality_Insights/blob/main/output_img/ss2.png)

![ScreenShot of personality form 1](https://github.com/pravincoder/Skills-Personality_Insights/blob/main/output_img/ss3.png)

![ScreenShot of personality form 2](https://github.com/pravincoder/Skills-Personality_Insights/blob/main/output_img/ss4.png)

![ScreenShot of Resume analysis 1](https://github.com/pravincoder/Skills-Personality_Insights/blob/main/output_img/ss1.png)

## Usage

1. Submit the Our Resume
2. Take personality Test
3. Answer the questions presented on the web interface.
4. Submit your responses.
5. View the generated personality chart based on your responses.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/new-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- This project was inspired by my friends in our Mini Project Mumbai university.
- Thanks to the streamlit,sklearn, Flask and Chart.js communities for providing excellent resources and documentation.
- Thanks to kaggle dataset [source](https://www.kaggle.com/datasets/tunguz/big-five-personality-test/data) .