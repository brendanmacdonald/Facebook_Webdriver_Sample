# Dependenices

### Java
Java v1.7 is required.

### Chromedriver
https://sites.google.com/a/chromium.org/chromedriver/downloads

### Selenium Server
http://www.seleniumhq.org/download/

## INITIAL SET-UP
1. Clone this repository.
2. Open in an IDE.
3. Install the Facebook Webdriver:
```
composer install
```
4. Start selenium server:
```
java -jar <<<name of the JAR file>>>
```
5. Execute tests with:
```
vendor/bin/phpunit SampleTestRemoteWebDriver.php
```
