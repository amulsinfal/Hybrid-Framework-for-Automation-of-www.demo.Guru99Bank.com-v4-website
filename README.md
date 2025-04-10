# Automation Project - Guru99Bank demo [Selenium | Java | TestNG | POM | Maven | Jenkins]

### 🌟 Project Title: 
Automation framework  for testing of [Guru99Bankdemo](https://www.demo.guru99.com/V4/)

### ⚡️ Project Overview:
This project aims to create an automated testing framework using the Selenium automation tool, Java as the programming language, TestNG as the testing framework, and following the Page Object Model (POM) design pattern. The target application for this project is the [Guru99Bankdemo](https://www.demo.guru99.com/V4/), which is a fictional online banking site for practicing and learning test automation.<br> 
<img width="1164" alt="chrome_4TIjcuQDYU" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/fec8f647-4049-434c-ae4e-e4f135c9fb11">

## ⚙️ Tools, Languages Frameworks used:

The project uses the following tools, frameworks:

| # | Tech/Tools | Name | Version |
| -------- |-------- | -------- | -------- |
| 1 | Programming language    | Java    | 17.0.8    | 
| 2 | Automation tool    | Selenium webdriver     | 4.14.1     |
| 3 | Testing framework | TestNG | 7.8.0 |
| 4 | Build Tool | Maven | 3.9.4 |
| 5 | IDE | Eclipse | 2023-09(4.29.0) |
| 6 | Reporting tool | Extent Reports | 5.1.1 |
 
## 📜 Project Structure : 
Following is the folder structure for this project : <br>

<img width="400" alt="explorer_zWQNXivWeh" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/b246a3e0-5683-4b15-9f64-3ddf3d7d4c92">

## 📜 Dependency using in the project:
Following are the dependencies added to the pom.xml for this project : <br>

| # | Name |  Version |
| -------- | -------- | -------- |
| 1 | Selenium java | 14.4.1 |
| 3 | TestNG | 7.8.0 |
| 4 | Extent Reports | 5.1.1 |
  
![image](https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/4006aef3-7836-4c50-a5a3-bab987a00771)

## 📜 Design Pattern used - Page Object Model:

**Page Object Model (POM)**: Implement the POM design pattern. This pattern involves creating separate classes for each distinct page or section of the website under test.<br>

**Page Classes**: Each page class encapsulates the web elements and methods required to interact with those elements on that specific page. This separation of concerns improves code maintainability.

Pages classes are saved under following path : "/guru99bankdemo/src/main/java/guru99bank/pages/" <br>

<img width="400" alt="qj1746UA4I" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/9278102f-0d59-45c6-b740-1520e537ee75">

## 📜 Test cases :

**Test Classes:** Test classes that correspond to different test scenarios or functionalities are created. Tests classes are saved under following path : "/guru99bankdemo/src/test/java/guru99bank/testcases/" <br> 

<img width="400" alt="D5Bg9KKgAf" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/8d7a9ce7-d130-4969-ab45-c70fe5649721">
<br>

Following are the test cases covered in the this Project:
1. Login into application.<br>
2. Creating customer.<br>
3. Verifying created customer.<br>
4. Create new account.<br>
5. Verifying created account.<br>
6. Logging out of the application.<br>

**TestNG Annotations:** TestNG annotations like @Test, @BeforeMethod, and @AfterMethod are used to organize test methods, setup, and teardown logic. <br>

**Page Object Usage:** In your test methods, initialize and use the page objects to interact with web elements on the pages under test.

## 📜 Test Data:

**Test Data:** Test data such as user id and password are saved in data.properties file, Other information like customer detials and account details are stored in data providers class.<br>
<img width="400" alt="MUIVHZG33X" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/ab38490b-c018-4a7c-bf4a-081455908e5f">

**DataProvider.java:**
![image](https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/af121f3e-e699-418d-936b-3383e879cf6f)

**data.properties file:**
![image](https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/56fea09f-5ad6-4efe-b8c4-efb5621a9a70)

## 📜 Reporting:

**Test Reporting:** Implemented test reporting using third-party reporting frameworks - ExtentReports. <br>
Reports are saved in the following location : "/guru99bankdemo/Reports/"<br>
<img width="400" alt="OHpyaBzM2K" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/1a8c8e2e-07e8-4f79-b593-ee51292e62a0"> <br>

Extent Report opened automatically on the default browser after the execution is completed.<br>
<img width="1260" alt="chrome_S2hWiML0zU" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/255c891a-b1f9-41da-a4f7-554982433861">
<img width="1260" alt="chrome_BniXRJRHB0" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/bbdaf290-f562-442d-899b-d094d44990b4">

## 🏃 Running the project:

### 🧪 Cloning the repository:
1. Clone [automation-framework-pom-selenium-java-testng-guru99bank](https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank.git) project from Github<br> 
  ```
    git clone https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank.git
  ```
2. Navigate to the cloned directory<br> 
  ```
    cd automation-framework-pom-selenium-java-testng-guru99bank
  ```   
3. Compile maven dependencies<br> 
  ```
    $ mvn compile
  ```

### 🔑 Site Credentials:
Guru99 Demo site credentials (Userid and password) are required to run test automation scripts. The userid and password will be available from the guru99 demo site homepage.<br> 

<img width="1260" alt="chrome_4TIjcuQDYU" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/962e6869-c9ae-4512-8e9d-45579a3cb398">

### 📖 Set the userid and password in the data.properties file:

Replace the value for userid key and password key in the data.properties file.<br>
<img width="1260" alt="MUIVHZG33X" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/56fea09f-5ad6-4efe-b8c4-efb5621a9a70"> <br>

### Running the Tests Locally:
Step 1. Navigate to the cloned directory<br> 
  ```
    cd automation-framework-pom-selenium-java-testng-guru99bank
  ```  
Step 2: Open command prompt and run the following command <br>
  ```
    mvn clean test
  ```  
  
Shown below is the execution screenshot triggered by the above command : <br>
<img width="900" alt="cmd_BAjX8FZ1ix" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/2dd12eb8-42c6-4f48-8ff4-457446d62927">  

Step 3: Extent Report open automatically on the default browser after the execution is completed.<br>
<img width="1260" alt="chrome_S2hWiML0zU" src="https://github.com/itsamul/automation-framework-pom-selenium-java-testng-guru99bank/assets/85364800/255c891a-b1f9-41da-a4f7-554982433861">
