# RSMethodValidation
This is a Python based Flask application that uses RS method to solve formulas and generate tree to determine its validity as a Tautology.

#### Installation Steps:

Install Virtual Env:

    pip install virtualenv
    
Test your installation:

    virtualenv --version

Switch to Virtual Environment:

    virtualenv venv

Install all the necessary packages:

    pip install -r requirements.txt

Confirm all the packages have been installed:

    pip freeze


Run the application in you virtual environment:

    python server.py

The application would start running on localhost and would provide you with the URL. Now open any browser and hit the above URL to access the application.

    Running on http://127.0.0.1:5000/



#### Sample input formulas:

|        Formula to Evaluate         |       Formula to enter in the text box        |
| :--------------------------------: | :-------------------------------------------: |
|            ((A→B)→A)→A             |              if(if(if(A,B),A),A)              |
| ¬(((a → b) ∧ (c → b)) → ¬(a ∧ ¬c)) | (if(and(if(a,b),if(c,b)),not(and(a,not(c))))) |


