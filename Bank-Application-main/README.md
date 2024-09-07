# Bank Application
Simulate Bank Application With Java and Database
------------------------------------
>***You need to do something before running the project***
</br></br>
**SQL Setting**</br></br></br>
For Setting Sql For This Application Please Create Database With Name Of (Bank) Then Import Sql Files In Our Repository(admin,clients,employees,newaccount,transfersreports) to your database.</br></br>
Attention That You Must Change (SignupController.java, EmployeeController.java, DButilsLS.java, CustomerController.java, AdminController.java) DB_URL,USER,PASS According To Your Sql Settings.</br></br>We Have Used MySql For Our Database If You Use Another Database Please Change DB_URL(jdbc:mysql://localhost:3306/bank) mysql To Whatever Database You Use Instead.</br></br>
And For The USER Default In mysql Is root...But If Your Username In Your Sql Is Another Thing Please Change This Too.</br></br>
In The End It's Obvious That You Must Change Change PASS To Your Database password.</br></br></br>
**External Libraries You Need To Import**</br></br>
All JavaFX Libraries And Also Connector J If Your Using mysql.(Default Place Of Connector J Is C:\Program Files (x86)\MySQL\Connector J 8.0)
</br></br>
After Adding All Needed Mentioned Libraries If You Have (Java FX Components Are Missing Problem) In Running  Main Class Please Add This vm-args In Your Configuration</br></br>
--module-path C:/Java/javafx-sdk-17.0.1/lib --add-modules javafx.controls,javafx.fxml
download links for Mysql, javafx, mysqljdbc:                                                                   
 [JavaFx](https://openjfx.io/#)                                                                                           
[Mysql](https://dev.mysql.com/downloads/windows/installer/8.0.html)                                                                     
[jdbcMysql](https://dev.mysql.com/downloads/connector/j/)                                                                         
------------------------------------
**Bank Application**</br></br>
>**Login And SignUp**</br></br>
Our Application Has 5 Main Sections Such As Login Page, SignUp Page, Customers Page, Admin Page, Employee Page</br></br>
In Login And Sign Up Page As You See Here You Can Login And Also Signu Up as New User.
![](https://github.com/alibabakhanlu12/Bank-Application/blob/main/ScreenShots/SignupPage.png)

#### in  the login page You can choose which page you will go to through the combo box (custom page, admin page, employee page) and each of these pages has a separate username and password.</br></br>
![](https://github.com/alibabakhanlu12/Bank-Application/blob/main/ScreenShots/login.png)
</br></br>
------------------------------------
>***Customer Page***</br></br>
The custom page has 6 separate sections which are:
1- Creat New Account                       
2- See Reports                                                    
3-  Calculate Your Profit                             
4- See Personal Inforamtion                          
5- Withdraw                                       
6 - Deposit                        
 
![](https://github.com/alibabakhanlu12/Bank-Application/blob/main/ScreenShots/CustomerPage1.png)
![](https://github.com/alibabakhanlu12/Bank-Application/blob/main/ScreenShots/CustomerPage2.png)
------------------------------------
>**Employee**</br></br>
>The Employee page has 6 separate sections which are:                                                              
>1 - see Reports                                                                                           
>2- Control Customers(Seeing Their Information Or Even Delet'em)                                                                                  
![](https://github.com/alibabakhanlu12/Bank-Application/blob/main/ScreenShots/EmployeeMainPage.png)
------------------------------------
>**Admin**</br></br>





