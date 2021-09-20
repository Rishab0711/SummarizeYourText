# Summary_Generator
Used Flask API to integrate,python script with a web application. Deployment is done on Heroku cloud platform. Following is the link to the web application:    https://glacial-dawn-61333.herokuapp.com/

# Requirements:
You must have following python libararies installed on your machine. Please refer to requirements.txt file for details.

1.Flask 

2.NLTK

3.Networkx

# Project structure:
The projects has following major parts:

1.app.py : Contains Flask APIs that receive inputs through GUI, calls the main python script for processing and returns the output.

2.summarizer.py : Contains python code to generate text summary from original text.

3.templates : Contains HTML files that allow user to interact with the application.

# Running the project:
1.Open Ananconda command prompt and move to your project home directory.

2.Run app.py using below command to start Flask API python app.py.

3.Navigate to the localhost to view the application home page.

4.Enter the text to summarize in the textbox and hit Summarize button.


# Screenshots

![1](https://user-images.githubusercontent.com/61036755/91711561-b5c4ed80-eba3-11ea-9f47-1d57096b5092.png)

![2](https://user-images.githubusercontent.com/61036755/91711569-b8bfde00-eba3-11ea-93f9-30332ce5bf96.png)


