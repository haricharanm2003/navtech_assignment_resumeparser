Resume Parser using Transformer Model

Objective :-

This project is built as part of the Navtech assignment. The goal is to develop a robust resume parser capable of handling files in .pdf, .docx, and .doc formats. 
The parser uses a Transformer-based NLP model to extract relevant information and outputs the results in JSON format.

Background :-

In modern digital recruitment, companies receive resumes in many formats. Manual screening is time-consuming and prone to error. Automating resume parsing ensures both speed and accuracy.
This parser uses Transformer models (e.g., BERT or GPT) to intelligently extract structured data from unstructured resume text.

Requirements Covered :- 

1. File Format Support
	•	Handles .pdf, .doc, and .docx files.

2. Transformer Model Integration
	•	Utilizes pre-trained Transformer models to comprehend and extract information from resume content.

3. Information Extracted
	•	Contact Information: Name, Email, Phone Number
	•	Education History: Institution, Degree, Graduation Year
	•	Work Experience: Company, Position, Description, Duration
	•	Skills
	•	Optional Sections: Certifications, Projects, etc.

4. Output Format
	•	Outputs the parsed information in JSON format for easy integration with other systems.

5. How to Use ??
	1.	Clone the repository
	2.	Upload a resume file (.pdf, .docx, or .doc)
	3.	Run the notebook (Navtech assessment.ipynb) in Google Colab or locally
	4.	View the extracted JSON output

6. Sample output :-

{
  "first_name": "",
  "last_name": "",
  "email": "",
  "phone": "",
  "address": {
    "city": "",
    "state": "",
    "country": ""
  },
  
  "summary": "",
  "skills": [
    {
      "skill": ""
    }
  ],
  
  "education_history": [
    {
      "degree": "",
      "name": "",
      "from_date": "",
      "to_date": ""
    }
  ],
  
  "work_history": [
    {
      "company": "",
      "title": "",
      "from_date": "",
      "to_date": "",
      "description": ""
    }
  ]
}
