# PSU-HelpBot-with-Langchain-Integration

## Introduction
PSU Helper is a project aimed at creating an effective Question Answering system for students seeking information related to graduate programs and computer science departments at Portland State University (PSU). This system utilizes advanced natural language processing techniques and technologies to provide fast, relevant, and accurate responses to student queries.

## Project Overview
PSU HelpBot utilizes a two-step approach:
1. **Data Collection:** Web scraping techniques gather information from various PSU department websites and other relevant sources.
2. **Question Answering:** Langchain, a natural language processing library, integrates with OpenAI's large language models to understand and answer user queries.

## Data Sources
The project scrapes data from the following sources:

- [Portland State University Engineering Department](https://www.pdx.edu/engineering/)
- [Departments and Programs at PSU Engineering](https://www.pdx.edu/engineering/departments-programs)
- [Portland State University Computer Science Department](https://www.pdx.edu/computer-science/)
- [Graduate Programs at PSU Computer Science Department](https://www.pdx.edu/computer-science/graduate)
- [Master's Program at PSU Computer Science Department](https://www.pdx.edu/computer-science/master)
- [Master's Track Courses at PSU Computer Science Department](https://www.pdx.edu/computer-science/masters-track-courses)
- [Google Spreadsheet - Graduate Information](https://docs.google.com/spreadsheets/d/1Zzyb9E1zLwQ0TYErZfoW9i2BM83b_PFba6zWmzMELQs/edit#gid=0)
- [Academic Programs at PSU Engineering](https://www.pdx.edu/engineering/academic-programs)
- [Graduate Candidate Deadlines at PSU](https://www.pdx.edu/gradschool/graduate-candidate-deadlines)
- [Graduate Tuition Information at PSU](https://www.pdx.edu/student-finance/tuition/graduate)
- [Graduate Programs in Computer Science at PSU](https://www.pdx.edu/academics/programs/graduate/computer-science)
- [Apply to Graduate School at PSU](https://www.pdx.edu/admissions/apply-to-grad-school)


## Models and Technologies Used
- Langchain: Facilitates web scraping and integrates with NLP models.
- OpenAI's Large Language Models (LLMs): Power the core question-answering functionality (Davinci-002, GPT-3.5-turbo-instruct).
- TextSplitter: Divide into chunks
- FAISS: Enables efficient similarity search for retrieving relevant information.
- TikToken: Performs text tokenization.

## Evaluation
- BERTScore: Measures semantic similarity between model outputs and expected responses.
- Human Evaluation: Assesses the system's accuracy, relevance, and user-friendliness through human testing.
- RAGAS: Retrieval-augmented generation with Attention Scoring for evaluating the system's ability to combine retrieval and generation tasks.

## Features
- Fast and accurate question-answering system
- Supports a broad range of questions related to PSU's graduate programs and computer science departments.
- Easy to use and integrate

## Usage
Access the deployed PSU HelpBot application here:
https://psu-buddy-dpmmaekkruxdlracwvfjfn.streamlit.app/

## Contributing
We welcome contributions to improve PSU HelpBot! If you're interested, feel free to fork the repository and submit pull requests.
