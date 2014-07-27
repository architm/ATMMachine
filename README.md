This project basically focuses on the Object Oriented Programming methods along with Client-Server Model which has been implemeted wit Java RMI.
 
Points To Note regarding the project:
1) Below are the steps for successfully running the project:
i) This project requires Java RMI, so 1st step is to include the jre bin path to environment variable.
ii) Compile and add the server registry and then run the bank project by following the below steps:
    javac RmiServer.java
	rmic RmiServer.java
	java RmiServer
iii) Now, in the new command line window run the client which will interact with the bank
     javac ATMMain.java
	 java ATMMain
Now, it will give you the interface something like the ATM Machine gives. :)

2) The ATM project structure is something like this
atm.client: ATMMain.java | ReceiveMesaageInterface.java |  SessionInfo.java
atm.physical: CashManager.java | ConsoleManager.java
atm.transaction: PinChange.java | Withdraw.java | DepositCheque.java | BalanceInquiry.java
atm.transaction: PinChange.java | Withdraw.java | DepositCheque.java | BalanceInquiry.java
...and the Banking project structure is:
RmiServer.java | ReceiveMessageInterface.java | BankDatabase.java
P.S. I haven't made the above project structure(included all the files in default package) due to some problem while running.

3) I have also included the design which i have followed while making this ATM Project and also made the Doc inside the code describing the working of code.

4) If you have any queries, kindly contact me at Mobile No.- 8978769074 or email-id: arma1303@gmail.com.