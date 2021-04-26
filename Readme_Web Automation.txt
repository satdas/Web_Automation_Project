1) Extract Section1 zip file.
2) Open Eclipse and click File > Import 
3) Select  Projects from Folder or Archive under General section in Import Window and click Next button.
4) Select folder - "Section1" after clicking Directory button to browse in Import Projects from File System or Archive window
5) Click Select All button
6) Click Finish
7) now you should see Project got imported
8) Right click on testng.xml file and select Run as- Testng Suite to trigger automation scenarios

3)Scenarios Covered:
  Test1 : To verify if one value selected in one dropdown ,value corresponding to the selected one should be visoble
          in another dropdown
  a) Go to https://moneycontrol.com/mf/returns-calculator.php
  b) Page should load with two dropdowns visible - Mutual Fund and Scheme
  c) Verify if under Mutual Fund dropdown - "Aditya Birla Sun Life Mutual Fund" is selected, then 3rd value from 
     Scheme dropdown should display "Aditya Birla Sun Life Active Debt Multi Manager FoF Scheme (D)"

  Test 2: To verify the text displayed in About Us page 
   a) Go to - https://finartis.com
   b) Click "About us"  menu
   c) New page should get loaded , verify that "Singapore" should appear in new Page under Our Offices section

  Test 3: To click submenu under Menu in website and check the text and title of page displayed after redirected page gets loaded
   a) Go to https://www.amazon.com/
   b) Hover mouse on "Account & Lists" section 
   c) Click on the submenu appearing after one hovers mouse as suggested in previous step - "Create a list"
   d) Verify the title of page appearing when "Create a list" submenu is clicked should be "Your List"
   e) Verify the text "Shopping List" should be displayed on page loaded
             