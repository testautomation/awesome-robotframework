# Awesome Robot Framework [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

 [![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Build Status](https://api.travis-ci.org/fkromer/awesome-robotframework.svg)](https://travis-ci.org/fkromer/awesome-robotframework)

[<img src="https://raw.githubusercontent.com/fkromer/awesome-robotframework/master/robot_framework_logo_new.png" align="right" width="86">](http://robotframework.org/)

> A curated list of awesome Robot Framework resources and libraries

## Contents

- [Trending](#trending)
- [Misc](#misc)
- [Libraries](#libraries)
- [Tools](#tools)
- [Resources](#resources)
- [Trainings](#trainings)

## Trending on Github
Trending [Robot Framework repositories](https://github.com/trending/robotframework) on Github

## Misc

- [docker-robot-framework](https://github.com/ppodgorsek/docker-robot-framework) Robot Framework (with Firefox and Chrome) in Docker.
- [robotkernel
](https://github.com/datakurre/robotkernel) RobotFramework kernel for Jupyter notebooks.

## Libraries

- Standard Libraries
  - [BuiltIn](http://robotframework.org/robotframework/latest/libraries/BuiltIn.html) Contains generic often needed keywords. Imported automatically and thus always available.
  - [Collections](http://robotframework.org/robotframework/latest/libraries/Collections.html) Contains keywords for handling lists and dictionaries.
  - [DateTime](http://robotframework.org/robotframework/latest/libraries/DateTime.html) Supports creating and verifying date and time values as well as calculations between them.
  - [Dialogs](http://robotframework.org/robotframework/latest/libraries/Dialogs.html) Supports pausing the test execution and getting input from users.
  - [OperatingSystem](http://robotframework.org/robotframework/latest/libraries/OperatingSystem.html) Enables performing various operating system related tasks.
  - [Process](http://robotframework.org/robotframework/latest/libraries/Process.html) Supports executing processes in the system.
  - [Screenshot](http://robotframework.org/robotframework/latest/libraries/Screenshot.html) Provides keywords to capture and store screenshots of the desktop.
  - [String](http://robotframework.org/robotframework/latest/libraries/String.html) Library for manipulating strings and verifying their contents.
  - [Telnet](http://robotframework.org/robotframework/latest/libraries/Telnet.html) Supports connecting to Telnet servers and executing commands on the opened connections.
  - [XML](http://robotframework.org/robotframework/latest/libraries/XML.html) Library for verifying and modifying XML documents.

- Mid level (framework) Libraries
  - [Android Library](https://github.com/lovelysystems/robotframework-androidlibrary) ([keyword documentation](http://lovelysystems.github.io/robotframework-androidlibrary/AndroidLibrary.html)) Library for all your Android automation needs. It uses Calabash Android internally.
  - [AnywhereLibrary](https://github.com/luisxiaomai/robotframework-anywherelibrary) Library for testing Single-Page Apps (SPA). Uses Selenium Webdriver and Appium internally.
  - [Appium Library](https://github.com/serhatbolsu/robotframework-appiumlibrary) Library for Android- and iOS-testing. It uses Appium internally.
  - [DjangoLibrary](https://kitconcept.github.io/robotframework-djangolibrary/DjangoLibraryDocs.html) Library for Django, a Python web framework.
  - [Drupal Library](https://github.com/alterway/robotframework-drupallibrary) Library targeting Drupal sites, built on top of Selenium2Library.
  - [Eclipse Library](https://github.com/lcarbonn/robotframework-eclipselibrary) Library for testing Eclipse RCP applications using SWT widgets.
  - [ImageHorizonLibrary](https://github.com/Eficode/robotframework-imagehorizonlibrary) ([keyword documentation](http://eficode.github.io/robotframework-imagehorizonlibrary/doc/ImageHorizonLibrary.html)) Cross-platform, pure Python library for GUI automation based on image recognition.
  - [iOS Library](https://github.com/lovelysystems/robotframework-ioslibrary) Library for all your iOS automation needs. It uses Calabash iOS Server internally.
  - [Page Object Library](https://github.com/boakley/robotframework-pageobjectlibrary) Library that makes it possible to use the page object pattern when testing web pages.
  - [Swing Library](https://github.com/robotframework/SwingLibrary) ([keyword documentation](http://robotframework.org/SwingLibrary/SwingLibrary-1.9.7.html)) Library for testing Java applications with Swing GUI.

- Low level (driver) Librabries
  - [AngularJS Library](https://github.com/Selenium2Library/robotframework-angularjs) An AngularJS extention library to Robotframework's Selenium2Library.
  - [Archive Library](https://github.com/bulkan/robotframework-archivelibrary) Library for handling zip- and tar-archives.
  - [AutoIt Library](https://code.google.com/archive/p/robotframework-autoitlibrary/) Windows GUI testing library that uses AutoIt freeware tool as a driver.
  - [Database Library (Java)](https://github.com/ThomasJaspers/robotframework-dblibrary) Java-based library for database testing. Usable with Jython.
  - [Database Library (Python)](https://github.com/franz-see/Robotframework-Database-Library) Python based library for database testing. Works with any Python interpreter, including Jython.
  - [Diff Library](https://bulkan.github.io/robotframework-difflibrary/) Library to diff two files together.
  - [Excel Library](https://github.com/NaviNet/robotframework-excellibrary) Library which provides keywords to allow opening, reading, writing and saving Excel files.
  - [FTP Library](https://github.com/kowalpy/Robot-Framework-FTP-Library) Library which makes it possible to test or use FTP server using Robot Framework keywords.
  - [HTTP Request (Java)](https://github.com/Hi-Fi/robotframework-httprequestlibrary) Library for HTTP level testing using Apache HTTP client.
  - [HTTP Request (livetest)](https://github.com/peritus/robotframework-httplibrary) Library for HTTP level testing using livetest tool internally.
  - [HTTP Request (Requests)](https://github.com/bulkan/robotframework-requests) Library for HTTP level testing using Request internally.
  - [IMAP Library](https://github.com/lovelysystems/robotframework-imaplibrary) Library to test mail validation tasks.
  - [JSON Schema Library](https://github.com/jstaffans/robotframework-jsonschemalibrary) JSON Schema validation library for Robot Framework.
  - [MongoDB Library](https://github.com/iPlantCollaborativeOpenSource/Robotframework-MongoDB-Library#readme) Library for interacting with MongoDB using pymongo.
  - [MQTT Library](https://github.com/randomsync/robotframework-mqttlibrary) Library that provides keywords for testing on MQTT brokers.
  - [NcclientLibrary](https://github.com/vkosuri/robotframework-ncclient) ([keyword documentation](https://vkosuri.github.io/robotframework-ncclient/)) Robotframework NETCONF wrapper library of ncclient.
  - [Rammbock](http://robotframework.org/Rammbock/latest/Rammbock.html) Generic network protocol test library that offers easy way to specify network packets and inspect the results of sent and received packets.
  - [Suds Library](https://github.com/ombre42/robotframework-sudslibrary) ([keyword documentation](http://ombre42.github.io/robotframework-sudslibrary/doc/SudsLibrary.html)) Library for functional testing of SOAP-based web services with Suds, a dynamic SOAP 1.1 client.
  - [UNIX Filesystem Library](https://github.com/ChrisHirsch/robotframework-unixfilesystem) Unix filesystem testing for Robot Framework.
  - [Debug Library](https://github.com/xyb/robotframework-debuglibrary) Debug Library for Robot Framework

## Tools

- Built-in tools
  - [DbBot](https://github.com/robotframework/DbBot) DbBot is a tool to serialize Robot Framework test run results into a SQLite database.
  - [Rebot](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#post-processing-outputs) Tool for generating logs and reports based on XML outputs and for combining multiple outputs together.
  - [RoboMachine](https://github.com/mkorpela/RoboMachine) Model-based testing with Robot Framework.
  - [Libdoc](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#libdoc) Tool for generating keyword documentation for test libraries and resource files.
  - [Pabot](https://github.com/mkorpela/pabot) Parallel executor for Robot Framework test cases.
  - [Testdoc](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#testdoc) Generates high level HTML documentation based on Robot Framework test cases.
  - [Tidy](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html#tidy) Tool for cleaning up and changing format of Robot Framework test data files.
  - [Remote Interface](https://github.com/robotframework/RemoteInterface) Introduction to the remote interface with a list of available remote servers.

- Build
  - [Jenkins plugin](https://wiki.jenkins.io/display/JENKINS/Robot+Framework+Plugin) Plugin to collect and publish Robot Framework test results in Jenkins.
  - [Robotcorder](https://chrome.google.com/webstore/detail/robotcorder/ifiilbfgcemdapeibjfohnfpfmfblmpd) Chrome plugin to record session for Robot Framework.  
  - [Maven plugin](http://robotframework.org/MavenPlugin/) Maven plugin for using Robot Framework.
  - [Ant task](https://github.com/lcarbonn/robotframework-ant) Ant task for running Robot Framework tests.

- Editors
  - Atom
    - [Atom Language Robot Framework](https://atom.io/packages/language-robot-framework) Robot Framework syntax highlighting for Atom
    - [Autocomplete Robot Framework](https://atom.io/packages/autocomplete-robot-framework) Robot Framework autocomplete for Atom
    - [Hyperclick Robot Framework](https://atom.io/packages/hyperclick-robot-framework) Robot Framework hyperclick provider for Atom
  - VSCode
    - [RobotF Extension](https://marketplace.visualstudio.com/items?itemName=kmk-labs.robotf-extension) Visual Studio Code extension for robot framework.

- Verification
  - [Robot Framework Lint](https://github.com/boakley/robotframework-lint) Linter for robot framework plain text files.

## Resources

- RoboCon 2019
  - [Welcome back! What's new since RoboCon 2018?](https://www.youtube.com/watch?v=wBhY5Z2RoqQ&index=2&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [The start of the open source RPA movement](https://www.youtube.com/watch?v=uv6dvcoxdvU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=2)
  - [Evolution of Robot Framework user](https://www.youtube.com/watch?v=ynUmfWvZxpw&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=3)
  - [Decade with SeleniumLibrary and browsers' UI automation](https://www.youtube.com/watch?v=HVAnWH8t4rU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=4)
  - [RobotFramework for Embedded Software Testing](https://www.youtube.com/watch?v=0q4-AjqpO9M&index=5&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [RENAT - a network testing plugin based on Robot Framework](https://www.youtube.com/watch?v=FSjmJLq4S4A&index=6&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Robot Framework with Patient Monitors: Test Automation at GE Healthcare Finland](https://www.youtube.com/watch?v=gxbz5QJWdq4&index=7&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Practical Experiences on Evaluating Software Testing Tools](https://www.youtube.com/watch?v=2qKa3GEqcvY&index=8&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Robots from Jupyter The Future of Authoring Tests and Tasks](https://www.youtube.com/watch?v=rbYF_RmiAR8&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=9)
  - [Dynamically scalable test environment on top of Kubernetes](https://www.youtube.com/watch?v=ivLsjU77Q6c&index=10&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Dynamic Generation of Model Based Testcases Using Listener Interface Version 3](https://www.youtube.com/watch?v=qtEYZ5Om1Qk&index=11&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning Talks I - robotframework-whitelibrary](https://www.youtube.com/watch?v=ck_zvTq4zz8&index=12&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning talk II](https://www.youtube.com/watch?v=a-27Ot_suEU&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&index=13)
  - [Lightning talk III - DevSecOps in embedded systems](https://www.youtube.com/watch?v=hA99dYnlb-s&index=14&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Lightning talk IV - Testing Complext Graphical Applications & Games with RobotFramework](https://www.youtube.com/watch?v=g98m3XpE8gw&index=16&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [Lightning talk V - Robot Framework Testing in Cloud](https://www.youtube.com/watch?v=YJ4FTjxVG3o&index=17&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt&t=0s)
  - [Lightning talk VI - Robot Framework: More than just automation](https://www.youtube.com/watch?v=9HHgrLb41go&index=17&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)
  - [Turning Test Results into Big Data](https://www.youtube.com/watch?v=fb42449bdz0&index=18&list=PLSK6YK5OGX1D-QpVap5C7NlfurQ1dsGbt)

- RoboCon 2018
  - [How Did We Get Here? Where Do We Go Next?](https://www.youtube.com/watch?v=6Kb1M3NECic&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z)
  - [The Naked Truth About Successful Test Automation Journey](https://www.youtube.com/watch?v=Z-9XIGZBf9U&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=2)
  - [Mega Robot Projects - What To Expect](https://www.youtube.com/watch?v=KsRP9TsZwEQ&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=3)
  - [Robot Framework in Plone CMS Project](https://www.youtube.com/watch?v=iJEWobuwPeI&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=4)
  - [The Importance of Open Source Communities](https://www.youtube.com/watch?v=2GDrtvz_1Ds&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=5)
  - [Towards Contract - Based API Testing with a New Rest Json Test Library](https://www.youtube.com/watch?v=TMU4WCIq3NA&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=6)
  - [Extending SeleniumLibrary 3.0](https://www.youtube.com/watch?v=ZPqQ-RozkYQ&index=7&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z)
  - [Design Patterns for Efficient Multi-Platform](https://www.youtube.com/watch?v=QDaXTkiviT0&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=8)
  - [Parallel test execution with Pabot](https://www.youtube.com/watch?v=i0RV6SJSIn8&list=PLSK6YK5OGX1AUdykW4DYwNeSN_6qDE_-z&index=9)

- Official Docs
  - [Robot Framework Introduction](https://github.com/robotframework/IntroSlides)
  - [Quickstart Guide](https://github.com/robotframework/QuickStartGuide/blob/master/QuickStart.rst)
  - [User Guide](http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.html)
  - [How To Write Good Test Cases](https://github.com/robotframework/HowToWriteGoodTestCases/blob/master/HowToWriteGoodTestCases.rst)

- Books
  - [Robot Framework Test Automation](https://www.packtpub.com/application-development/robot-framework-test-automation) :heavy_dollar_sign:

- MOOCs
  - [Robot Framework Test Automation - Level 1 (udemy)](https://www.udemy.com/robot-framework-level-1/) :heavy_dollar_sign:
  - [Robot Framework Test Automation - Level 2 (udemy)](https://www.udemy.com/robot-framework-2/) :heavy_dollar_sign:
  - [Robot Framework Test Automation - Saucelabs Integration (udemy)](https://www.udemy.com/robot-framework-saucelabs-integration/) :heavy_dollar_sign:
  - [Robot Framework - Jenkins CI & Git Version Control (udemy)](https://www.udemy.com/robot-framework-jenkins-git/) :heavy_dollar_sign:

- Theses
  - [Data-Driven and Keyword-Driven Test Automation Frameworks](http://eliga.fi/Thesis-Pekka-Laukkanen.pdf) Master's Thesis, Pekka Laukkanen
  - [Web  Application  Test  Automation  with  Robot Framework](https://www.theseus.fi/bitstream/handle/10024/93164/Thesis_Jani_Luostarinen_v1_0.pdf?sequence=1) Bachelor's Thesis, Jani Luostarinen

## Trainings

- Face-to-Face
  - [Testautomatisierung mit dem Robot Framework - Intensivtraining (codecentric)](https://www.codecentric.de/leistungen/loesungen/wir-bauen-erfolgreiche-software/agile-software-factory/robot-framework/) :heavy_dollar_sign:
  - [Test Automation using Robot Framework (tesena)](http://www.tesena.com/test-automation-using-robot-framework/) :heavy_dollar_sign:
  - [Scripting a Robot framework utilizing Python](http://www.softwareskillnet.ie/course/87/scripting-a-robot-framework-utilizing-python-/) :heavy_dollar_sign:
- Live
  - [Robot Framework Online Training (prezi)](https://prezi.com/f_omeuiv3ok5/robot-framework-online-training/) :heavy_dollar_sign:
  - [Robot Framework Certification Training (sulekha)](https://techjobs.sulekha.com/robot-framework-training) :heavy_dollar_sign:
