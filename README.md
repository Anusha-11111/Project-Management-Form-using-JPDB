# Micro- project work 
# Title of the Project Management Form using JPDB

LINK - https://github.com/Anusha-11111/Project-Management-Form-using-JPDB.git

Description : Project Management Form that will store data in PROJECT-TABLE relation of COLLEGE-DB database
              Input Fields: {Project-ID, Project-Name, Assigned-To, Assignment-Date, Deadline}, Primary key: Project ID
              
Benefits of using JsonPowerDB : Simplest way to retrieve data in a JSON format. Schema-free, Simple to use, Nimble and In-Memory database. It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX. It is low level (raw) form of data and is also human readable. It helps developers in faster coding, in-turn reduces development cost. Release History (release of your JsonPowerDB related code on Github)

Additional you can have: JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

Illustartions:
Created a Project management form. The form stores data in the database.

There will be three control buttons [Save], [Update] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key in the relation. All other fields and buttons will be disabled at this time.

User will enter data in the field having primary key(Project Id) and

- If the primary key value does NOT exist in the database, enable [Save] and [Reset] buttons and move the cursor to the next field and allow the user to enter data in the form.

Checks that the data should be valid i.e. no empty fields.

Complete the data entry form and click the [Save] button to store the data in the database.

- If the primary key value is present in the database, display that data in the form. Enable [Update] and [Reset] buttons and move the cursor to the next' field in the form. Keep the primary key field disabled and allow users to change other form fields.

Check that the data should be valid i.e. no empty fields.

Click on [Update] button to update the data in the database.

Click [Reset] to reset the form to enter new data.

![Screenshot (47)](https://github.com/Anusha-11111/Project-Management-Form-using-JPDB/assets/112841894/4cfdb2be-941a-492a-b6a9-0af2906bd51e)
![Screenshot (48)](https://github.com/Anusha-11111/Project-Management-Form-using-JPDB/assets/112841894/68a2e6c1-64a9-4a5d-8bbd-6382b3bdc3e9)
![Screenshot (49)](https://github.com/Anusha-11111/Project-Management-Form-using-JPDB/assets/112841894/e57d8290-ce58-447a-96c9-9efa494a9e68)


Project status : Done

Sources :Introduction to JsonPowerDB - V2.0 https://careers.login2explore.com/course/view.php?id=14

Other information Sources : https://login2explore.com/jpdb/docs.html

# STEP BY STEP COURSE DOCUMENTATION :
JsonPOwerDB
Introduction to JsonPowerDB - V2.0 Login2Xplore

Creating a Developer Account and Generating Connection Token : -

Visit: http://api.login2explore.com:5577/user/index.html REGISTER After registration check your email-id for password. Login at http://api.login2explore.com:5577/user/index.html using your email and password received. First of all change password - Left Navigation >> Change Password. Login with new password.

Tools > Token > connection token > Generate (Token needed to communicate with Data Base)

Token used to execute the API

Installing Talend API Tester : -

Google > settings > Extensions > Chrome Web store > Talend API Tester - Free Edition > Add to chrome extension

Creat environment CRUD operations:
PUT Command - Creating (Inserting) RecordPage
GET Command - Retrieving RecordPage
UPDATE Command - Update a recordPage
REMOVE Command - Remove a recordPage

We will learn about AJAX - Asynchronous JavaScript And XML for creating web page using netbeans and chromuim.

Netbeans should be Installed and chromium tool should be installed for hands on experience to create web page.

Then micro -project follows(code is uploded>>index.html)


