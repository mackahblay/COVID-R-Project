# COVID-R-Project
You are a Junior Analyst at Sigalo Research, a Clinical Research Organization (CRO) that specializes in making vaccinations and other drugs for infectious diseases. 
Your company has been awarded $50 million to conduct preliminary research on COVID-19 in hopes of developing a vaccination for the rapidly spreading virus. Your 
boss and Senior Researcher, Dr. Nikki Sigalo, has tasked you with conducting the preliminary descriptive analysis and presenting the results to the rest of the research team.
The datasets, coronavirus.xlsx Download coronavirus.xlsx and comorbid.xlsx Download comorbid.xlsx, consist of patients that have been held for quarantine across the world,
some with COVID-19 and some without COVID-19. Her email to you is linked here:

From: Nikki Sigalo
To: Junior.Analyst@SigaloResearch.com 
Subject: COVID-19 Exploratory Data Analysis Report 

Dear Analyst,  
Welcome to the team! We recently received international patient data that will allow us to conduct a preliminary analysis of COVID-19 patients, in hopes of informing the development of our new drug, COVIDA. I would like for you to  conduct a descriptive, exploratory analysis on these patients and disseminate the results to the rest of the team prior to our quarterly all-staff meeting. Please see the requirements below (Note: there must be a line(s) of code  for each bullet below. Each line of code must have a comment that clearly indicates what that line is doing):  
Data cleaning/preparation (suppress output, awarnings, and messages from this code chunk) 
Import coronavirus.xlsx and comorbid.xlsx  
Merge the two datasets, keeping observations that exist in both files  
We will assume that any age values greater than or equal to 120 are implausible. If Age is greater than  or equal to 120, recode Age to NA  
The Country variable contains two different values for China. Recode any values of ‘Mainland China’ to ‘China’  
Exploratory Data Analysis (suppress output, awarnings, and messages from this code chunk)
Find the number of observations  
Find the number of variables  
What percentage of patients are female?  
What is the median age of patients who have coronavirus?  
What is the mean age and standard deviation of patients who died from coronavirus?  
Among patients who have coronavirus, what percentage are from each of the following countries:  China, Italy, and the US?  
What are the comorbidities (with percentages) associated with patients who have coronavirus?  
Data Visualization (OPTIONAL - Extra Credit)
Create a boxplot of the age variable, by the coronavirus variable  
 Your graph MUST have a title and axis labels. 
After conducting the analysis, produce a report in HTML (you MUST use R Markdown for this). The report must  have a header with the following information: Title: “Coronavirus Exploratory Data Analysis” and Author (Your name). The  report should have 5 sections (each section header must be formatted as a Level 1 Header):  
Introduction (Min. 100 words)  
In a narrative (with references, APA format), provide background information on COVID-19, including:  
How it spreads  
Symptoms  
Prevention/Treatment  
Describe who is at higher risk of developing serious symptoms 
Data Cleaning/Preparation (Min. 100 words)  
In a narrative, explain the data cleaning and preparation steps taken to prepare the dataset (as described in  1a-1d above)  
Exploratory Data Analysis (no word minimum, but you must address each of the bullets from 2a-2g for this)
In a narrative, present the findings of the exploratory data analysis in 2a-2g above. For example, your  paragraph for this section must explain what you found: “The dataset consisted of x observations and x  variables. X% of patients in this dataset were female….” Round all values to one decimal point.
Data Visualization (OPTIONAL - EXTRA CREDIT - Min. 50 words)   
In a narrative, explain what the boxplot illustrates
References  
Bibliography/reference list in APA format  
Looking forward to reading your report!  
Best,  
Dr. Nikki Sigalo  
______________________________ Nikki Sigalo, PhD, MPH 
Senior Researcher  
Sigalo Research  
5555 1st St. NE, 12th Floor  
Washington, DC 20002-4221  
Phone: 555-838-3603 




Extra Credit: The data visualization section is optional. We will not cover data visualization until after Spring Break, but if you would like to do some research & take a stab at a simple data visualization, you will be granted extra points (2 points).

Note: All narratives must use Markdown text formatting (i.e. do NOT use R comments for narrative text. R comments are for annotating your code only). Please refer to the Module 2 In-Class Exercise for more information on working with R Markdown.  You must submit your .Rmd file AND your HTML file for full credit. You must structure your markdown file as follows (an example is also attached here

):

Header (Level 1)

Narrative (using Markdown text)

Code Chunk that does what you discussed in the narrative

In order to receive full points, your code should be displayed in the HTML file, but you must SUPPRESS warnings, messages, and output from all code chunks EXCEPT for the code chunk that shows your boxplot (i.e. the data visualization section) if you choose to do the extra credit section. This means you should not have any R output except for your boxplot (if you choose to do the extra credit). Failure to abide by this formatting will result in the loss of points.
