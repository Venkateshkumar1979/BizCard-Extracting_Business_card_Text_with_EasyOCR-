# Demo video of the project:https://www.linkedin.com/posts/venkatesh-kumar-s-b3293a59_python-mysql-streamlit-activity-7080316032933859328--zzT?utm_source=share&utm_medium=member_desktop
# BizCard-Extracting_Business_card_Text_with_EasyOCR
## About the Project
A Streamlit application was developed that allows users to upload an image of a business card and extract relevant information from it using EasyOCR library in Python 3.11. The extracted information includes the company name, card holder name, designation, phone number, email id, website URL, address and pin code. 
The extracted information is then displayed in the Streamlit application's GUI.
In addition, the application allows the users to save the extracted information into a MySQL database along with the uploaded business card image. The database will be able to store multiple entries, each with its own business card image and extracted information.
To achieve this, Python, Streamlit, EasyOCR, and a database management system like MySQL has been used. 
The application has a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. 
The extracted information is displayed in a clean and organized manner, and users will be able to easily add it to the database with the click of a button. Also, it allows the user to perform CRUD operations (Create, Read, Update, Delete) on the stored data through the Streamlit UI.
# Methodology
## Packages Used.
•	Python 3.11
•	MySQL Workbench
•	Streamlit GUI
## Libraries used
•	Pandas - (To Create a DataFrame)
•	mysql.connector - (To perform CRUD operations on the uploaded MySQL database)
•	Streamlit - (For Graphical User Interface (GUI))
•	EasyOCR - (To extract text from images)
•	RE (for regex operations)
•	OS (for file handling)
## Roadmap
1.	Installing the required packages.
2.	Designing the user interface: Created a simple and intuitive user interface using Streamlit that guides users through the process of uploading the business card image and extracting its information. Widgets like file_uploader, buttons, and text boxes are used to make the interface more interactive.
3.	Implementing the image processing and OCR: Use EasyOCR to extract the relevant information from the uploaded business card image. The image was converted to greyscale before passing it to the OCR engine to enhance the quality of extraction.
4.	Display the extracted information: Once the information has been extracted, displayed it in a clean and organized manner in the Streamlit GUI. Widgets like tables, text boxes, and labels are utilised to present the information.
5.	Implementing database integration: Database management system like MySQL was used to store the extracted information along with the uploaded business card image. CRUD operations can be done through the Streamlit UI
6.	Testing the application: The application was thoroughly tested to ensure that it works as expected. The application was tested on the local machine by running the command streamlit run ocr6.py in the terminal, where ocr6.py is the name of the Streamlit application file.
