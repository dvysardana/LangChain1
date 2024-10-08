Explanation of files in the repo:

1. Flask_Api.ipynb
Python notebook containing code for Flask API to query SQLite database based on input queries and return response.

2. LangChain.ipynb
Python notebook containing code for Langchain to understand Professor's intent and query the Flask API to get SQL results and answer back in natural language.

3. Flask_Api.html and LangChain.html
html files containing snapshots of all the cells of corresponding notebooks in a working state.

4. student.db
SQLLite db file containing data for Students and Scores that can be used to demonstrate the usecases in the code. Note that code to create these tables and insert values in them using Langchain has been provided as commented out lines in the Python notebooks.


Steps to Run:
1. Download Flask_Api.ipynb, LangChain.ipynb and student.db in the same directory.
2. Open the jupyter notebook, Flask_Api.ipynb and run all the cells. This will make sure the Flask server is up and running.
3. Open the jupyter notebook, LangChain.ipynb and run all the cells. Note than an openapi key will be required in one of the cells.
4. No extra installation steps are required.

NOTE: Extensive comments have been added to both the Python notebooks to explain the prerequisites, running and testing instructions and the details of all steps.
For any further questions, please email me at divya.sardana@gmail.com.
