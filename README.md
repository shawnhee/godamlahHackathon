-- HR's Matchmaker: Talent recruiter --
Steps to run:
1. Open the folder in an IDE such as PyCharm Community Edition
2. Change the API and Project ID to your own key in app.py
- Visit JamAIBase website, create an account, set the organization name to any name (Don't worry, it doesn't affect its functionality)
- Create a project of your own prefered name, go into your project and import the action table .parquet file that is in the folder "JamAIBase Action Table"
- To get your JamAIBase API Key, go to **organization>secrets>create API key**
- To get your project ID, go to your project, click the three lines beside your project name, there you can copy your project ID
3. Install streamlit framework by running "**pip install streamlit**" in terminal
4. Make sure you are running on **python version 3.10**
5. Run the site by running "**streamlit run app.py**"
  - You may test the system by uploading some of our available CVs in the **CV Sample** folder
 
How does it work?
1. Upload interviewee's cv file
2. Enter company's job description
3. sit back, relax, the system will generate a report. You may download the report for reference.

Happy matching!
