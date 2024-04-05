# Resume-Identification-using-LLM
# Problem Statement: Find out best 5 resume for appropriate skill set from list of resumes.
# Solution:
 Using Open AI model and vector databases it is solved. I toolk 50 resume pdf files and first read all files using Pypdf parser.
 Then for each pdf file converted pdf into text and separate into paragraphs then using Open AI model I converted all text into vector databases and stored into Single Store Database.
 Now user can give any skill set to the code and code gives us the best 5 resume which matches best with particular skill set. 
