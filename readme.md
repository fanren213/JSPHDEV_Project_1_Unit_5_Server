#README
Bonan Cao <bonanc@andrew.cmu.edu>
Feb. 27. 2016
This directory holds the the JAVA project for project 1 Unit 5 PartA of 18-641, the class diagram and the outputs of project. The details are as follows.

Two projects are included:
- Server
- Client
The client is updated in this unit while the server part is the same as last unit.

Test: 
1. run the server use ServerDriver
2. run the client with console UI use ClientDriver and add automobiles to the server:
	- select option 1 in the main menu and use the properties file included in 		the client part: 1.properties, 2.properties, 3.properties and 4.properties.
3. run the Tomcat with client part and type http://localhost:8080/Project_1_Client/ in the address bar of your browser.

The drivers for client and server are in package client and server of two projects respectively. There are three servlets in client, for selection of auto, selection of options and return the result and price. Two java server pages are used in the last two steps. Tomcat 8.0 is used when testing the project.

The outputs of test are shown in test_output_1.png, test_output_2.png and test_output_3.png.
The diagram is shown in class_diagram_client.png and class_diagram_server.png.
The list of files:
  ▾ bonanc_Project1_Unit5/
    ▾ Project_1_Client/
      ▾ bin/
        ▾ adapter/
            BuildAuto.class
            CreateAuto.class
            EditAuto.class
            FixAuto.class
            ProxyAutomobile.class
            UpdateAuto.class
        ▾ client/
            CarModelOptionsIO.class
            ClientDriver.class
            DefaultSocketClient.class
            SelectCarOption.class
        ▾ constants/
            ClientConstants.class
            SizeConstants.class
        ▾ exception/
            AutoException.class
            ExceptionEnum.class
            FixHelper.class
        ▾ model/
            Automotive.class
            OptionSet$Option.class
            OptionSet.class
        ▾ scale/
            EditOptions.class
        ▾ servlet/
            ModifyAuto.class
            SelectAuto.class
            ShowChoice.class
        ▾ util/
            FileIO.class
      ▾ src/
        ▾ adapter/
            BuildAuto.java
            CreateAuto.java
            EditAuto.java
            FixAuto.java
            ProxyAutomobile.java
            UpdateAuto.java
        ▾ client/
            CarModelOptionsIO.java
            ClientDriver.java
            DefaultSocketClient.java
            SelectCarOption.java
        ▾ constants/
            ClientConstants.java
            SizeConstants.java
        ▾ exception/
            AutoException.java
            ExceptionEnum.java
            FixHelper.java
        ▾ model/
            Automotive.java
            OptionSet.java
        ▾ scale/
            EditOptions.java
        ▾ servlet/
            ModifyAuto.java
            SelectAuto.java
            ShowChoice.java
        ▾ util/
            FileIO.java
      ▾ WebContent/
        ▾ META-INF/
            MANIFEST.MF
        ▾ WEB-INF/
          ▸ lib/
            web.xml
          ModifyAuto.jsp
          ShowChoice.jsp
        1.properties
        2.properties
        3.properties
        4.properties
        exception.log
        Ford Focus Wagon ZTW.dat
        Ford Focus Wagon ZTW.txt
        representations.aird
    ▾ Project_1_Server/
      ▾ bin/
        ▾ adapter/
            BuildAuto.class
            CreateAuto.class
            EditAuto.class
            FixAuto.class
            ProxyAutomobile.class
            UpdateAuto.class
        ▾ constants/
            ClientConstants.class
            SizeConstants.class
        ▾ exception/
            AutoException.class
            ExceptionEnum.class
            FixHelper.class
        ▾ model/
            Automotive.class
            OptionSet$Option.class
            OptionSet.class
        ▾ scale/
            EditOptions.class
        ▾ server/
            AutoServer.class
            BuildCarModelOptions.class
            DefaultSocketClient.class
            Multithread.class
            ServerDriver.class
        ▾ util/
            FileIO.class
      ▾ src/
        ▾ adapter/
            BuildAuto.java
            CreateAuto.java
            EditAuto.java
            FixAuto.java
            ProxyAutomobile.java
            UpdateAuto.java
        ▾ constants/
            ClientConstants.java
            SizeConstants.java
        ▾ exception/
            AutoException.java
            ExceptionEnum.java
            FixHelper.java
        ▾ model/
            Automotive.java
            OptionSet.java
        ▾ scale/
            EditOptions.java
        ▾ server/
            AutoServer.java
            BuildCarModelOptions.java
            DefaultSocketClient.java
            Multithread.java
            ServerDriver.java
        ▾ util/
            FileIO.java
        exception.log
        Ford Focus Wagon ZTW(with wrong format).txt
        Ford Focus Wagon ZTW(without basePrice).dat
        Ford Focus Wagon ZTW(without basePrice).txt
        Ford Focus Wagon ZTW.dat
        Ford Focus Wagon ZTW.txt
        representations.aird
      class_diagram_client.png
      class_diagram_server.png
      readme.txt
      test_output_1.png
      test_output_2.png
      test_output_3.png
