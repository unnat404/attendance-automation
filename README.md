 # attendance-automation
Automates the process of manually marking attendance from screenshots! 

## Process
1. For a given set of screenshots of participants/attendees of a meeting with names of format :
`<Last 3 digits of roll_no>_<Name>`
2. Extract the text from screenshots via an OCR (using pytesseract) 
3. Clean the obtained text
   * duplicate removal
   * unwanted/unapproved charector removal 
4. Mark attendees present/absent => 1/0 in the excel sheet (using openpyxl)

## Work Flow
![image](https://user-images.githubusercontent.com/53619178/146436992-4dd266ad-b76b-44b9-88f5-284863e66d80.png)
