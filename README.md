# AI Resume Screening & Candidate Ranking System

This project uses AI and machine learning to rank resumes based on a given job description. By extracting and processing text from uploaded resume PDFs, the system compares the content of the resumes with the job description and ranks them according to their relevance. The system leverages the **TF-IDF** vectorization and **cosine similarity** to measure the similarity between resumes and job descriptions.

## Features
- **Job Description Input**: Allows the user to input the job description for the position.
- **Resume Upload**: Enables users to upload multiple resumes in PDF format.
- **Resume Ranking**: Ranks resumes based on their relevance to the job description using AI-based algorithms.
- **Custom Styling**: Custom CSS for a hover effect on the "Rank Resumes" button to enhance user interaction.

## Technologies Used
- **Streamlit**: A fast web framework for building data apps.
- **PyPDF2**: A Python library for extracting text from PDF files.
- **Pandas**: For handling and manipulating the data (resumes and scores).
- **Scikit-learn**: For implementing machine learning algorithms like TF-IDF and cosine similarity.

## Installation

To run the project locally, follow these steps:

### 1. Clone the repository:
```bash
git clone https://github.com/Adi2212/AI-Resume-Screening-Candidate-Ranking-System
```

### 2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

The `requirements.txt` file should contain the following libraries:
```
streamlit
PyPDF2
pandas
scikit-learn
```

### 3. Run the Streamlit app:
```bash
streamlit run app.py
```

The app will launch in your default browser, allowing you to interact with the system.

## How to Use
1. **Enter the Job Description**: In the "Job Description" section, paste the job description for the role you're hiring for.
2. **Upload Resumes**: In the "Upload Resumes" section, upload one or more PDF resume files.
3. **Rank Resumes**: Click the **Rank Resumes** button to rank the uploaded resumes based on how well they match the job description.
4. **View Results**: The results will be displayed in a table format, sorted by the relevance score.

## Customizations
- You can customize the UI by modifying the CSS code in the app, such as changing button styles, colors, or animations.
- The scoring algorithm can be tweaked by modifying the TF-IDF vectorizer settings or using different machine learning models.



