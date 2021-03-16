# JPDB-Employee Form
## by [Login2Xplore](http://login2explore.com/index.php)
Has 3 buttons - [Save], [Change], [Reset]

On page load an empty form will be displayed and the cursor will remain at empID. All buttons will be disabled at this time.
 - User will enter empID
 - If empID does NOT exist in the database, enable [Save] and [Reset] buttons and move the cursor to the next field. 
 - Complete the data entry form and use [Save] button to store the data in file or use [Reset] button to reset the form for step-1.
 - If empID is present in the database, display that data in the form. Enable [Change] and [Reset] buttons and move the cursor to the empName field. Also disable the empID field. 
 - Modify the data in the form and click on [Change] button to update this record in the database or click the [Reset] button to reset the form for step-1.


![](/public_html/images/Emp-Exist.png)
![](/public_html/images/Emp-New.png)
