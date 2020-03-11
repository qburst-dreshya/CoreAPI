# Regression / Smoke testing using Maven
This project is for SIT regression and smoke testing.

## Prerequisite 
```
JAVA 1.8+

Maven
```

## Installation 
```
git clone https://github.com/qburst-arunr/fr-qa-jmeter.git

cd fr-qa-jmeter

mvn install
```

## Execution using Maven 

Regression suite
```
mvn clean verify -Dsuite=Regression
```
Smoke suite
```
mvn clean verify -Dsuite=Smoke
```
## Reports
After execution is done reports will be generated in below folder.
```
 <PROJECT FOLDER> target> jmeter> reports
```
# Regression / Smoke testing using JMeter

## Prerequisite 
```
JAVA 1.8+

JMeter

repository - git clone https://github.com/qburst-arunr/fr-qa-jmeter.git

```

## Configure JMeter to add include directory 
```
Navigate to JMeter home folder> bin

Edit jmeter.properties file with the following edit

includecontroller.prefix= <BASE PATH>\FRfinaldemo\API\src\test\jmeter\
```
## Execute scripts from JMeter

```
Navigate to JMeter home folder> bin

Start JMeter using jmeter.sh / jmeter.bat

Open file from <BASE PATH>\FRfinaldemo\API\src\test\jmeter\JMX\<Regression/Smoke>\<file>
```
 


