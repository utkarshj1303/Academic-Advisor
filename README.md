# Academic Advisor

Acadmic Advisor is an Android Application that aggregrates data from the UW Course Guide, Rate My Professors and UW Madison Course Grade Distribution. The app generates a list of courses based on the users selected range of professor rating, range of average gpa and L&S requirement which they wish to satisfy. This was submitted as the final project for UW - Madison's CS 506 Software Engineering course.

The project consists of a frontent which is an Android application and a server which starts the scrapers and then stores the scraped data in a database which the Android application then queries. 

Iteration 1 <11/1/2017> 

Iteration 2 <11/27/2017>

Instructions:
1.	Logon to GitHub and search for “tyleroconnell/adademicadvisor”; 
2.	Click on the green button “Clone or download” to download the zip file of this project to your local computer;
3.	Unzip the file to your working folder;
4.	Download and install the newest version of Android Studio;
5.	Launch Android Studio and open the project from "File -> Open..." by choosing the root folder of the unzipped file;
6.	Press Shift + F10 or click on the "Run" button on the tools bar;
7.  To run the MyCourseGuideScraper, first install selenium, lxml, beautifulsoup, requests and json for python
8.  Install Firefox and the selenium geckodriver for your OS.
9.  Change path in line 145 of CourseGuideScraper.py to the location of geckodriver on your computer and then run the python program.
10. The output of the CourseGuideScraper is in the data.txt file in the out folder.
10. For RmpScraper, add the jar's for the jsoup and simple json libraries. 
11. For PdfScraper, add the PDFBox jar. Also make sure the Course Grade Distribution .pdf documents are in the same directory as the program.
12. The CourseGuideTest.py needs to be in the same directory as the CourseGuideScraper.py. Run the CourseGuideTest.py.
13. The PdfScraper_Test and RmpScraperTest can be run directly.

For the API,
1. Open IntelliJ
2. Click Import Project
3. Navigate to the directory of "academicadvisor/backend/api" from the repo you cloned and click Open
4. Make sure "Create module from existing sources" is selected and click Next
5. Edit the project the name if you wish and click Next
6. Make sure "academicadvisor/backend/api/src/main/java" and "academicadvisor/backend/api/src/test/java" are both selected and click Next
7. Make sure "gradle-wrapper" is selected from the library and click Next
8. Make sure "academicadvisor/backend/api/src/main/java" and "academicadvisor/backend/api/src/test/java" are both selected and click Next
9. Select the path to your Java SDK for Project SDK and click Next
10. Click Finish
11. Build | Rebuild Project
12. Run Application
