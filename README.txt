# Introduction:
You are tasked with developing key features which encompasses distinct problem statements, each targeting a crucial area within the Data/ML/AI domain. Your work will directly contribute to the usability and efficiency of our platform, enhancing user experience and providing valuable insights.  

Note: Install all the dependencies from requirements.txt before execution

Overall repository hierarchy:  
├── Source_code  
│   ├── Task1  
│   │   ├── data_engineer.py  
│   │   └── EDA  
│   │       ├── eda_task1.py  
│   │       ├── EDA_Task1.ipynb  
│   │       ├── EDA_Task1.pdf  
│   │       └── data_final.csv  
│   ├── Task2  
│   │   ├── File_metadata.csv  
│   │   └── file_similarity.py  
│   │   └── Data  
│   │       ├── education_data13.txt  
│   │       ├── education_data15.pdf  
│   │       ├── education_esaay20.pdf  
│   │       ├── education_essay1.docx  
│   │       ├── education_essay10.txt  
│   │       ├── education_essay11.txt  
│   │       ├── education_essay12.txt  
│   │       ├── education_essay16.pdf  
│   │       ├── education_essay17.pdf  
│   │       ├── education_essay18.pdf  
│   │       ├── education_essay19.pdf  
│   │       ├── education_essay2.docx  
│   │       ├── education_essay3.docx  
│   │       ├── education_essay4.docx  
│   │       ├── education_essay5.docx  
│   │       ├── education_essay6.docx  
│   │       ├── education_essay7.docx  
│   │       ├── education_essay8.txt  
│   │       ├── education_essay9.txt  
│   │       ├── education_summary14.pdf  
│   │       ├── entertainment_data16.pdf  
│   │       ├── entertainment_data17.docx  
│   │       ├── entertainment_essay1.txt  
│   │       ├── entertainment_essay11.docx  
│   │       ├── entertainment_essay12.pdf  
│   │       ├── entertainment_essay13.pdf  
│   │       ├── entertainment_essay14.docx  
│   │       ├── entertainment_essay15.pdf  
│   │       ├── entertainment_essay18.pdf  
│   │       ├── entertainment_essay19.pdf  
│   │       ├── entertainment_essay2.txt  
│   │       ├── entertainment_essay20.pdf  
│   │       ├── entertainment_essay3.txt  
│   │       ├── entertainment_essay4.txt  
│   │       ├── entertainment_essay5.txt  
│   │       ├── entertainment_essay6.txt  
│   │       ├── entertainment_essay7.docx  
│   │       ├── entertainment_essay8.docx  
│   │       ├── entertainment_essay9.pdf  
│   │       ├── entertainment_summary10.docx  
│   │       ├── health_data12.txt  
│   │       ├── health_data14.docx  
│   │       ├── health_essay1.pdf  
│   │       ├── health_essay10.pdf  
│   │       ├── health_essay11.docx  
│   │       ├── health_essay15.docx  
│   │       ├── health_essay16.docx  
│   │       ├── health_essay17.pdf  
│   │       ├── health_essay18.txt  
│   │       ├── health_essay19.txt  
│   │       ├── health_essay2.docx  
│   │       ├── health_essay20.txt  
│   │       ├── health_essay3.docx  
│   │       ├── health_essay4.docx  
│   │       ├── health_essay5.pdf  
│   │       ├── health_essay6.txt  
│   │       ├── health_essay7.txt  
│   │       ├── health_essay8.txt  
│   │       ├── health_essay9.docx  
│   │       └── health_summary13.docx  
│   └── Task3  
│       ├── Data_pdf.pdf  
│       ├── gold_answers.txt  
│       ├── questions.txt  
│       └── task3_rag_faq.py  
│── Executed_ipynb_files  
│    ├── EDA_Task1.ipynb  
│    ├── Task2_File_similarity.ipynb  
│    │── Task3_RAG_FAQ.ipynb  
│    └── PDF_ipynb_files  
│        ├── EDA_Task1.pdf  
│        ├── Task2_File_similarity.pdf  
│        └── Task3_RAG_FAQ.pdf  
│── Documentation  
│   ├── Task1_report  
│   ├── Task2_report  
│   └── Task3_report  
│── README.txt  
└── requirements.txt  






## Retrieve and Analyze Goodreads Data 

### File hierarchy 
├── Task1  
│   ├── data_engineer.py  
│   └── EDA  
│       ├── eda_task1.py  
│       ├── EDA_Task1.ipynb  
│       └── data_final.csv  


Note: data_final.csv is generated after data_engineer.py is executed  

In order to execute the scrapping, the command is as follows:
python data_engineer.py

In order to perfrom EDA after data_final.csv is extracted, the command is as follows:
python eda_task1.py

To check the python notebook where the EDA is already perfromed, open ** EDA_Task1.ipynb **

#### Dependencies needed to be installed priorly: (using pip)
bs4





## File Similarity Detection

### File hierarchy 
    ├── Task2  
    │   ├── File_metadata.csv  
    │   └── file_similarity.py  
    │   └── Data  
    │       ├── education_data13.txt  
    │       ├── education_data15.pdf  
    │       ├── education_esaay20.pdf  
    │       ├── education_essay1.docx  
    │       ├── education_essay10.txt  
    │       ├── education_essay11.txt  
    │       ├── education_essay12.txt  
    │       ├── education_essay16.pdf  
    │       ├── education_essay17.pdf  
    │       ├── education_essay18.pdf  
    │       ├── education_essay19.pdf  
    │       ├── education_essay2.docx  
    │       ├── education_essay3.docx  
    │       ├── education_essay4.docx  
    │       ├── education_essay5.docx  
    │       ├── education_essay6.docx  
    │       ├── education_essay7.docx  
    │       ├── education_essay8.txt  
    │       ├── education_essay9.txt  
    │       ├── education_summary14.pdf  
    │       ├── entertainment_data16.pdf  
    │       ├── entertainment_data17.docx  
    │       ├── entertainment_essay1.txt  
    │       ├── entertainment_essay11.docx  
    │       ├── entertainment_essay12.pdf  
    │       ├── entertainment_essay13.pdf  
    │       ├── entertainment_essay14.docx  
    │       ├── entertainment_essay15.pdf  
    │       ├── entertainment_essay18.pdf  
    │       ├── entertainment_essay19.pdf  
    │       ├── entertainment_essay2.txt  
    │       ├── entertainment_essay20.pdf  
    │       ├── entertainment_essay3.txt  
    │       ├── entertainment_essay4.txt  
    │       ├── entertainment_essay5.txt  
    │       ├── entertainment_essay6.txt  
    │       ├── entertainment_essay7.docx  
    │       ├── entertainment_essay8.docx  
    │       ├── entertainment_essay9.pdf  
    │       ├── entertainment_summary10.docx  
    │       ├── health_data12.txt  
    │       ├── health_data14.docx  
    │       ├── health_essay1.pdf  
    │       ├── health_essay10.pdf  
    │       ├── health_essay11.docx  
    │       ├── health_essay15.docx  
    │       ├── health_essay16.docx  
    │       ├── health_essay17.pdf  
    │       ├── health_essay18.txt  
    │       ├── health_essay19.txt  
    │       ├── health_essay2.docx  
    │       ├── health_essay20.txt  
    │       ├── health_essay3.docx  
    │       ├── health_essay4.docx  
    │       ├── health_essay5.pdf  
    │       ├── health_essay6.txt  
    │       ├── health_essay7.txt  
    │       ├── health_essay8.txt  
    │       ├── health_essay9.docx  
    │       └── health_summary13.docx  



In order to execute the python script for file similarity detection, the command is as follows:  
python file_similarity.py

To check the python notebook, open File_similarity.ipynb



#### Dependencies needed to be installed priorly: (using pip)  
PyPDF2  
python-docx  
contractions  
unidecode  





## Implementation of a Retrieval-Augmented Generation Model for a FAQ System 

### File hierarchy 
├── Task3  
    ├── Data_pdf.pdf  
    ├── gold_answers.txt  
    ├── questions.txt  
    └── task3_rag_faq.py  



In order to execute the script, the command is as follows:  
python task3_rag_faq.py

#### Dependencies needed to be installed priorly: (using pip)  
datasets  
sentence-transformers  
faiss-cpu  
accelerate  
bitsandbytes  
pypdf   
langchain_community  
langchain-text-splitters  
langchain  
nltk 
rouge-score
