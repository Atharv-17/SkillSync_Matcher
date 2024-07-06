# skillsync_matcher
A Flask web application to match resumes against a job description using cosine similarity of TF-IDF vectors. The application can extract text from PDF, DOCX, and TXT files and compare them with a job description to find the best matching resumes.

## Features

- Upload resumes in PDF, DOCX, or TXT format.
- Enter a job description.
- Extract text from the uploaded resumes and job description.
- Uses TF-IDF vectorization to represent text.
- Calculates cosine similarity to find the top matching resumes.
- Displays the top 5 matching resumes along with their similarity scores.

## Libraries

- Flask
- docx2txt
- PyPDF2
- scikit-learn (TfidfVectorizer, cosine_similarity)


## Usage of Project

1. **Navigate to the web application**:
    Open your web browser and go to `http://127.0.0.1:5000/` after running the Flask application.

2. **Enter the job description**:
    Type or paste the job description text into the provided text area.

3. **Upload resumes**:
    Click the "Choose Files" button to upload one or more resumes in PDF, DOCX, or TXT format.

4. **Submit the form**:
    Click the "Match" button to submit the job description and resumes for processing.

5. **View the results**:
    The application will display the top 5 matching resumes along with their similarity scores.
