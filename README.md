# Research-Paper-Parser
Usage

Run the application: streamlit run research.py

Upload research papers (PDF format) via the sidebar.
Select the data categories for extraction (e.g., Key Findings, Research Gaps, Methodology, etc.).
Click on Start Extraction to process the PDFs.
View extracted insights in collapsible sections.
Download the extracted data in CSV format.

The tool extracts information based on the following predefined categories:
Key Findings: Results and conclusions from the study.
Research Gaps: Unexplored areas and unanswered questions.
Methodology: Approaches, techniques, and frameworks used.
Limitations: Challenges and constraints faced in the study.
Future Work: Suggestions for further research.
Contributions: Novel aspects and advancements introduced by the research.
Practical Implications: Real-world applications and industry impact.

Technologies Used
Python: Core programming language.
Streamlit: Web framework for interactive UI.
PyPDF2: PDF text extraction.
TextBlob: NLP library for sentence parsing.
Pandas: Data manipulation and CSV export.
