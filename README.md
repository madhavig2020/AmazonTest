# AmazonTest - Automating Search for Headphones keyword and adding Best Seller items to Cart.

#Prerequisite:
Install  Java 1.8 & setup Environment Variables path.
Install any IDE.

##Set Up:

	• Create a simple Maven Project in Eclipse IDE.
	• In Pom.XML add dependency for Selenium Webdriver
	
		<!-- https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java -->
		<dependency>
					<groupId>org.seleniumhq.selenium</groupId>
					<artifactId>selenium-java</artifactId>
					<version>3.14.0</version>
				</dependency>
				
#	Chrome Driver Setup
	
	Download the Chrome Driver  from the link below.
	https://sites.google.com/a/chromium.org/chromedriver/
	In my case , I have saved the executable in c:\\chromedriver.exe
	I have to pass the Chrome driver executable as System property & passed in the Script.
	
#	How to Run:
	• In the above created Maven Project , create a package
	• Then create a new Java class & paste all the code present in the repository mentioned below
	• https://github.com/madhavig2020/AmazonTest/blob/master/AmazonBestSellerCart
	• Execute the code . Run as Java Application
	
	#Test Scenario:
	1. Open www.amazon.com website. 
	2. Enter the text “Headphones” in the search box. Hit enter 
	3. From the results displayed on page 1 add all the items marked as “Best seller” to the cart.  
