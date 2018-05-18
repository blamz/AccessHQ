# AccessHQ
Files for AccessHQ and related personnel only.

Project Name:
Phileas Trip

Description: 
A short selenium java demo. 
Opens the NSW Trip Planner site and runs a search.

Installation:
To run the base program, "Phileas Trip.jar", install the following:
* Java Software Development Kit (JDK) 10 - http://www.oracle.com/technetwork/java/javase/downloads/index.html
  * Click Java Platform (JDK) 10 in link
  * Accept the License Agreement
  * Click on the JDK that corresponds to your OS to download
  * Run the executable and follow the onscreen instructions, the default settings are okay
  * Note: if the above JDK is not compatible with your machine, e.g. 32 bit machine, you may find and use another version
*  Google Chrome - https://www.google.com.au/chrome/
  * Click download Chrome
  * Run the executable and follow the onscreen, the default settings are okay.

To run the source code, "Phileas Trip_Source", in addition to the above, install the following:
* Eclipse Java Oxygen 3a (or preferred IDE with Java support) - http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/oxygen/3a/eclipse-java-oxygen-3a-win32-x86_64.zip
  * Click Download
  * Unzip the contents, eclipse is ready to run directly
*	Google Chrome Driver 2.38 - https://chromedriver.storage.googleapis.com/index.html?path=2.38/
  * Click on the chromedriver for your operating system to download
  * Unzip the contents, the executable will be referenced in eclipse
*	Selenium WebDriver for Java 3.12.0 - https://www.seleniumhq.org/download/
  * Note: this is packaged in the source code
  * Locate the correct link on the page, listed under "Selenium Client & WebDriver Language Bindings" and in line with "Java"
  * Click Download
  * Unzip the contents, the jar files will be imported into eclipse.
* TestNG
 * Note: this is packaged in the source code
 * Instructions to install are listed in usage section

Note: 
* The links are suggestions, you may use your own source
* The programs are recommended for the best experience.
      
Usage:

Base program: 
* Simply run "Phileas Trip.jar" and observe the results.

Source code: 
* Open eclipse
* Use eclipse to open "Phileas Trip_Source.jar"
* Update the file path in code to point to the current location of chrome driver on your system
* Click run in eclipse and observe the results.

Importing Selenium files:
* If the packaged files in the source code do not work, then follow these steps:
 * With the project open in eclipse, right click on the "PhileasTrip" project in the package explorer window
 * Click properties
 * Click Java Build Path
 * Click Classpath
 * Click Add External JARs
 * Navigate to the Selenium files on your system
 * Select all JAR files in the libs folder and click Open
 * Click Add External JARs again
 * Select the JAR files outside the lib folder too and click Open
 * Click Apply and Close
 
Installing TestNG:
 * Inside eclipse, click help
 * Click eclipse marketplace
 * In the find window, type testng
 * Click on the magnfiying glass to begin the search
 * Look for "TestNG for Eclipse" and click install
 * Follow the on screen instructions; default settings are okay and simply agree to everything
 * Eclipse will need to restart after installing

Contributions:
Thanks goes to https://www.guru99.com/ for their great tutorials!

Licenses:
* Oracle license: http://www.oracle.com/technetwork/java/javase/terms/license/index.html
* Java SE license: http://www.oracle.com/technetwork/java/javase/documentation/java-se-lium-2018-03-19-4421425.pdf
* Eclipse license: http://www.eclipse.org/legal/epl-2.0/
* Selenium license (Apache 2.0 License): https://www.seleniumhq.org/about/license.jsp
* ChromeDriver - no licensing information: https://github.com/SeleniumHQ/selenium/wiki/ChromeDriver
