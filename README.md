# TourRadar
This project is a POM framework in selenium using Java as scripting language. Maven is used for dependency management and continuous development. TestNG is used to maintain test cases


I have add page objects for Login page, home Page, Tour Listings page under src/main/Java under Pageobjects package.
I have added 1 base file under src/main/java/TourRadar/TourRadar/ which has beforemethod and aftermethod tests which are used to initate the driver based on the browser parameter passed from textng file. (Ex: Chrome/firefox) and qutting the driver respectively
I have used ExtentReporting for the project which saves the report under Reports older after succesful run.

I have 1 TestCases class file in which main Test method is present
Flow of the Test case:
1. Login with existing user id
2. Search for India Tours
3. Sort with Highest price First
4. Download the brochure of a tour and view the tour details

I have added 2 tests in my testng.xml file. one for test running on chrome and one for test running on firefox.

I have add the testng.xml file in pom.xml file.

Downlaod project in your local machine and Import Project as exisitng maven project. After imporitng, use 'mvn clean' command Use 'mvn test' to execute test cases.
