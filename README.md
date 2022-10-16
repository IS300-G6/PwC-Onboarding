# PwC-Onboarding

## How to run the project
1) Install UI path
2) Clone the repository in UI path
3) Go to Main.xaml
4) Make sure you have an excel file with the following format stored somewhere on the computer
![image](https://user-images.githubusercontent.com/24401134/196056489-fc96d7dc-6ab4-4b1a-be6f-9126e201fabf.png)

5) Press 'Debug file' button -> then select 'Run'
![image](https://user-images.githubusercontent.com/24401134/196056460-b36a2c33-d1cf-463b-8e20-cfba6c33c353.png)

6) Select the excel file when the prompt shows up

## Description
  The functionality of this RPA is to gather the information when a client signs up. The bot will extract data and provide it to the manager of the project in an easy-to-use format. The application will scrape business data and information from Companies Register and Dun & Bradstreet business Directory. All the data extracted will be outputted onto an Excel sheet and the errors encountered will be reported in a PDF format.
  The procedure of this RPA software will start off reading the companies form an Excel file, then the bot will gather information for each company. The information would include Dunn And Brad Information, Company Register Information. The bot will begin it’s process by opening an Excel file and reading through the first column, recording any errors it may encounter=such as file does not exist into the error variable. Then bot will find the company register information from the website and retrieve all available relevant data for the company’s register info. The bot will fill in as many details as it can gather from the website and the data it has collected, while outputting the rest which cannot be found as NULL, the NULL values will be outputted into the error report in the end. After the company register info has been documented, the bot will move ahead to collect Dun And Brad Street Information. The bot will find the company on the website and it will retrieve relevant data and information for the company and will fill in as many details as possible from the data gathered, the rest that are unfounded will be documented as NULL. The NULL values will be explained in the error report. Once the bot finishes gathering the information of each company, it will output the results into an Excel file. The bot will open an Excel file and write in all the information it has gathered for each company into the excel file with the correct column headings. At last, once the bot has finished all it’s process of gathering information and outputting it in to an Excel file, the bot will begin to generate an error report containing all the errors it have encountered during the operations. The bot will open a word document and start documenting all the errors it has encountered during the entire process. Once the documentation of the error report in completed, the bot will create a PDF file and output the error report into a PDF format, after the error report PDF has been generated, the bot will then proceed to delete the word file it has created before the PDF file used to document the errors.
