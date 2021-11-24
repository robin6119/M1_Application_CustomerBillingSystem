# REPORT

 ## CUSTOMER BILLING SYSTEM

             Customer Billing System Project is a simple console application designed to demonstrate the 
    practical use of C programming language and its features as wells as to generate an application
    which can be used in any departmental store, shops, cafes etc. for billing to the customer.
  You can use this application to keep the records such as name, address, mobile number, paid amount,
    due amount, payment date etc. of your regular costumer. Moreover, if you have a new customer, 
    you can add and edit the account at any time.

 ## FEATURES OF CUSTOMER BILLING SYSTEM:-

 The Customer Billing System has :

   * Add and maintain records of available products.
   * Add and maintain customer details.
   * Add and maintain description of new products.
   * Add and maintain new entered category of products.
   * Provides economic/financial reports to the owner monthly or weekly and
     yearly.
   * Provides a convenient solution of billing pattern.
   * Make an easy to use environment for users and customers.

## IDENTIFYING THE REQUIREMENTS

## Technologies and Tools Used

     Web Technology: Chrome
     Development Tool: Github Website
     Web Server: IIS
     Web browser: Google Chrome Latest
     Languages Used: C Language
     Hardware CPU configuration
Intel processors

     RAM 4 GB DDR4 Operating System -Windows 10,Linux(Ubuntu)
     
 ## STATE OF ART:-

    PROBLEM OF EXISTING SYSTEM
                        
                        
     1. Inability of modification of data: The managing of huge data
        effectively and efficiently for efficient results, storing the details of the
        consumers etc.
     2. Not user friendly: The existing system is not user friendly because
        the retrieval and storing of data is slow and data is not maintained
        efficiently.
     3. Difficulty in reports generating: Either no reports generating in a
        current system or they are generated with great difficulty reports take
        time to generate in the current system.
     4. Manual operator control: Manual operator control is there and lead
        to a lot of chaos and errors.
     5. Lot of paperwork: Existing system requires lot of paper work and
        even a small transaction require many papers fill. Moreover any
        unnatural cause (such as fire in the organization) can destroy all data of
        the organization. Loss of even a single paper led to difficult situation
        because all the papers are interrelated.
     6. Inability of sharing the data: Data cannot be shared in the existing
        system. This means that no two persons can use the same data in
        existing system. Also the two departments in an organization cannot
        interact with each other without the actual movement of data.
     7. No support in decision-making: Existing system does not support
        managerial decision-making.
    8. No support in strategic competitive advantage: Existing system do
       not support strategic competitive advantages.


   CHARACTERSTIC OF THE PROPOSED SYSTEM
         
         
    1. Easiness in modification of data: The proposed system provides
       managing of huge data effectively and efficiently for efficient results,
       storing the details of the customers, employees etc. in such a way that
       the database can be modified.
    2. User friendly: The proposed system is user friendly because the
       retrieval and storing of data is fast and data is maintained efficiently.
       Moreover the graphical user interface is provided in the proposed
       system,which provides user to deal with the system very easily.
    3. Reports are easily generated: Reports can be easily generated in a
       proposed system. So any type of reports can be generated in a proposed
       system, which helps the managers in a decisions-making activity.
    4. Sharing the data is possible: Data can be shared in proposed system.
       This means that two or more persons can use the same data in existing
       system provided that they have right to access that data. Also the two
       or more departments in an organization can easily interact with each
       other without the actual movement of data.
    5. No or very few paperwork: The proposed system either does not
       require paper work or very few paper works is required. All the data is
       feted into the computer immediately and various bills and reports can be
       generated through computers. Since all the data is kept in a database no
       data of the organization can be destroyed. Moreover work becomes very
       easy because there is no need to keep data on papers.
    6. Support strategic competitive advantage: Proposed system supports
       strategic competitive advantages. Since the proposed systems provide
       easiness in reports generating it will provide strategic advantages among
       competitors.
    7. Computer operator control: Computer operator control will be there
       no errors. Moreover storing and retrieving of information is easy. So
       work can be done speedily and in time.
       
 ## SWOT ANALYSIS:-

 Strength:

`It is an automate application method ,so It will reduce the Human power.`
 Weakness:

`Though it is an Automated process, it is not fully automated.`
 Opportunities:

 `It will Increase the company efficiency.
 Requires less man power in IShops etc...`
 Threads:

  `By using this automation process, sometimes system might get corrupt.
  Provide false Information about the Customer.`
  
 4W'S AND 1H:-

 Why:

* This project will help the store keeper in fast billing
* This project enable store keeper to maintain a great database of all
 customers visited and purchase product from store.
* Project will enable to see report regarding product and category.
* Easy to maintain in future prospect.
 What:

`* Add and maintain records of available products.
* Add and maintain customer details.
* Add and maintain description of new products.
* Add and maintain new entered category of products.`
## Where:

`* Departmental stores
* Medicals.
* Shops etc..`
## When:
`* While Billing the products in shops.
* Billing in medicals etc`

 How:

`This Web based application automate the process of Ordering and billing of departmental store.`

 HIGH LEVEL REQUIREMENTS:-

|ID|Description	Status|
|---|---|
|HLR_1|customer Information Portal	Implemented|
|HLR_2|Products List area	Implemented|
|HLR_3|Fully Automated Tool	Future|

## LOW LEVEL PRQUIREMENTS:-

|ID|Description	Status|
|---|---|
|LLR_1|Invoice Area	Implemented|
|LLR_2|History Transactions Portal	Implemented|

## DESIGN DIAGRAMS

 Behavioural1

![Behavioural1](https://user-images.githubusercontent.com/94118694/142579077-0264e97c-89a3-49a3-b078-7169a8f921b4.jpeg)

 Behavioural2

![Behavioural2](https://user-images.githubusercontent.com/94118694/142579143-10f3593f-66c6-4fe5-a442-39f0465f2da3.jpeg)

 Structural1

![Structural](https://user-images.githubusercontent.com/94118694/142579502-1980cf57-5091-4646-95ca-473fdc9e89b9.jpeg)

 Structural2

![Structure2](https://user-images.githubusercontent.com/94118694/142579515-a33a6230-65ef-439c-ac91-d36c3e0d8350.jpeg)

## IMPLEMENTATION

 Instructions to execute

`* Clone my repository
* Go to 3_Implementation folder
* Make sure your system meets all software and hardware requirements
* Run "make run" command in terminal for main code execution
* Run "make run_test" command in terminal for test code execution`

|Folder|Description|
|---|---|
|inc|Contains header files|
|src|Contains additional source file for compilation|

## TESTPLAN

## TABLE NO:HIGH LEVEL TEST PLAN:

|Test ID|Description|Exp I/P|Exp O/P|Actual O/P|Type of Test|
|---|---|---|---|---|---|
|H_01|Check and verify all the product Price is entered or not|Enter the selected productID number|Price of the product is displayed|price of the product is displayed|Requirement Based|
|H_02|Check whether entered product is displayed correctly or not|Enter productID Number|Product is displayed|Product is displayed|Scenario Based|
|H_03|Check whether entered productID is correct|ProductID|Display product name|Display product name|Boundary Based|

## TABLE NO:LOW LEVEL TEST PLAN:

|Test ID|Description|Exp I/P|Exp O/P|Actual O/P|Type of Test|
|---|---|---|---|---|---|
|L_01|To check each product must show its original cost|ProductID|Product displayed with cost price|Product displayed with cost price|Requirement Based|
|L_02|To check the product entered without quantity|ProductID and quantity|Display Product and quantity|Display Product and quantity|Scenario Based|
|L_03|To check when quantity is given immediately it must multiply with cost price|Product ID and quantity|Multiplied priceand output|Multiplied price|Boundary based|
