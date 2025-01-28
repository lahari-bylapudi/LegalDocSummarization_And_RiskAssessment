# LegalDocumentSummarization_And_RiskAssessment

### Project Description
This project is designed to generate concise, context-specific summaries of legal documents and identify implicit risks The project also includes real-time monitoring and integration of regulatory updates into contract analysis. An interactive dashboard is provided for legal teams to streamline document review and risk assessment.

### Features
Generation of concise summaries for legal documents.
Identification of hidden risks and obligations through detailed analysis.
Real-time monitoring and updates of regulatory changes.
Interactive dashboard for efficient document review and risk assessment.

### Installation
To install the necessary libraries and modules for this project, you can use the provided requirements.txt file. Run the following command:
pip install -r requirements.txt

### Usage
Legal Document Summarization
The Legal_Document_Summarization.ipynb notebook provides the functionality to upload and process legal documents, split them into chunks, and create a searchable database using embeddings.

Risk Analysis
The Risk_Analysis.ipynb notebook includes functions to load and preprocess documents, detect risks, generate recommendations, and save the analysis results into a JSON file. It also demonstrates how to load the JSON data and extract contexts, analyses, and recommendations for display.

Interactive Dashboard
The App.py script sets up an interactive dashboard using Streamlit. Users can upload a document (txt, pdf, csv) for legal and risk analysis. The dashboard displays the document preview, risk analysis results, and allows sending the results via email.

### License
This project is licensed under the MIT License.
