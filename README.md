# POCSO_dataset
This repository contains data of POCSO Dataset presented in NLLP at EMNLP 2024 "Cross Examine: An Ensemble-based approach to leverage Large Language Models for Legal Text Analytics"
Author : 
1. Saurav Chowdhury , Indian Institute of Technology, Jodhpur , India email: chowdhury.4@iitj.ac.in
2. Suyog Joshi, Ashoka University, India email: suyog.joshi_asp25@ashoka.edu.in
3. Dr Lipika Dey, Ashoka University, India, email: lipika.dey@ashoka.edu.in

Paper Link: To be updated
# Abstract:
Legal documents are complex in nature, describing a course of argumentative reasoning that is followed to settle a case. Churning through large volumes of legal documents is a daily requirement for a large number of professionals who need access to the information embedded in them. Natural language processing methods that help in document summarization with key information components, insight extraction and question answering play a crucial role in legal text processing. Most of the existing document analysis systems use supervised machine learning, which require large volumes of annotated training data for every different application and are expensive to build. In this paper we propose a legal text analytics pipeline using Large Language Models (LLM), which can work with little or no training data. For document summarization, we propose an iterative pipeline using retrieval augmented generation to ensure that the generated text remains contextually relevant. For question answering, we propose a novel ontology-driven ensemble approach similar to cross-examination that exploits questioning and verification  principles. A knowledge graph, created with the extracted information, stores the key entities and relationships reflecting the repository content structure. A new dataset is created with Indian court documents related to bail applications for cases filed under Protection of Children from Sexual Offences (POCSO) Act, 2012 an Indian law to protect children from sexual abuse and offences. Analysis of insights extracted from the answers reveal patterns of crime and social conditions leading to those crimes, which are important inputs for social scientists as well as  legal system.
# Disclaimer:
The dataset shall be used solely for research purposes. No part of it, in whole or in part, shall be used for any commercial purpose.
# Dataset:
Dataset link : Please Fill up the form [POCSO Dataset Request Form](https://forms.gle/ms7mqoScaN9kkowu5) , to get access of POCSO_dataset.

#Instruction to use the dataset
The datset contains summary of 50 POCSO cases created using pipeline discussed in the above mentioned paper using 1. LLAMA2 and 2. GPT 3.5 

The Court Documents as mentioned in the dataset index is available on the folder named "files" in the dataset shared with you.
The summaries are available in the Google Sheet provided. The Google sheet contains 5 columns   Sl No., 	Case Document Name,	Date of Document, Creation	indiankanoon.org Link - summary of case,	LLAMA2 generated Summary using approach - using summaries of summaries and	GPT3.5 generated Summary using approach - using summaries of summaries

![image](https://github.com/user-attachments/assets/aa58fe6a-6f77-4e84-bf2b-014b04e782bb)

a. The Sl No column refers to the case number and corresponds to the document number in the files folder, which contains the court copy or original document.

b. The Case Document Name contains the case name followed by the date of the document.

c. The indiankanoon.org Link - Summary of Case column provides a direct link to the human-generated summary of the case on IndianKanoon.

d. LLAMA2 generated Summary using approach - using summaries of summaries and	GPT3.5 generated Summary using approach - using summaries of summaries contains the summaries created against the cases using approach discussed in the paper.

You are requested to cite our paper if you use any part of the dataset or paper for your work. Please contact authors in case of any query.
# Citation link: to be updated
# Acknowledgement
https://indiankanoon.org/, https://ecourts.gov.in/ecourts_home/
