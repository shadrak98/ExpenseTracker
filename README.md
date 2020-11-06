![Expense Tracker](https://github.com/shadrak98/ExpenseTracker/blob/master/logo_black.png)
----------------------------------

# Expense Tracker
An Android app that helps store images of their invoices and details fetched from Machine Learning Model in Database.

### Features:
* The app allows user to take pictures of their images and sends it to the server in the backend.
* **_It runs the Tesseract OCR over the image and gives the output in the textfile._**
* **_After getting the textfile, it extracts the necessary details such as Vendor Name, Date, Amount, Address, Invoice ID etc from the textfile and sends it back to the app._**
* For extracting details, **Bi-Direction Long Short-Term Memory (LSTM)** model is used on the server.


### ScreenShots:
Screenshots | Screenshots | Screenshots
:----------------:|:----------------:|:----------------:
![Login](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/login.jpeg) | ![Signup](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/register.jpeg) | ![Bills](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/list.jpeg)
----------------------------------------------------------------
* The App also allows users to see past bills and stores their images in **Firebase Database.**
* User can also view the expenses in form of __Piechart__.
* For Displaying piechart, [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart/) is used.
-----------------------------------------------------------
Screenshots | Screenshots | Screenshots
:----------------:|:----------------:|:----------------:
![Camera](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/cameraa.jpeg) | ![Verification](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/verify.jpeg) | ![Graph](https://github.com/shadrak98/ExpenseTracker/blob/master/Screenshots/chartt.jpeg)

### Technologies/Tools used:
* **Firebase** (Database)
* **Tesseract OCR** (OCR)
* **Flask** (Server)
* **Camera2 API** (Camera)
* **MPAndroidChart** (Piechart)

#### Team Members:
* Mukund Choudhary
* [Shadrak Gurupnor](https://github.com/shadrak98)
