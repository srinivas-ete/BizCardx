# BizCardX: Extracting Business Card Data with OCR
BizCardX is a powerful tool designed to streamline the process of extracting information from business cards using Optical Character Recognition (OCR). Whether you're a business professional, networking enthusiast, or simply looking to organize your contacts more efficiently, BizCardX is here to help.

## Workflow Diagram

![Workflow Diagram](https://blog.advance.ai/hs-fs/hubfs/OCR-implementation_02.jpg?width=1566&name=OCR-implementation_02.jpg)

## Features
# Efficiency:
Say goodbye to manual data entry and tedious typing. With BizCardX, extracting information from business cards is fast, accurate, and hassle-free.
# Accuracy: 
Our state-of-the-art OCR engine ensures high accuracy in extracting text from images, even from complex business card designs.
# Customization: 
Tailor the extracted information to suit your needs. Edit, format, and organize the data according to your preferences.
# Database Integration:
Seamlessly integrate with database management systems like MySQL or SQLite to store and manage your extracted business card data.

## Getting Started
1. Installation: Clone this repository to your local machine and install the required dependencies.
2. Database Setup: Ensure you have MySQL installed and running on your machine. Create a new database named business_cards and execute the SQL script create_table.sql to create the necessary table for storing card data.
3. Running the App: Launch the Streamlit app by running streamlit run app.py in your terminal. The app will be accessible in your web browser at http://localhost:8501.

## Usage
1. Upload a Business Card: Click on the "Upload" option in the menu and choose a business card image file (in PNG or JPEG format) to upload.
2. Extract Information: After uploading the image, click the "Extract Information" button to perform OCR and extract text from the image.
3. Review and Modify: Review the extracted text and modify any information if necessary.
4. Save to Database: Click the "Save to Database" button to store the extracted data in the MySQL database.
5. View and Manage Data: Use the "Modify" option in the menu to view, update, or delete stored business card data.

## Contributing
Contributions are welcome! If you have any ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request.
