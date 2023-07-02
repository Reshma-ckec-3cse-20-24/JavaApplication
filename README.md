# JavaApplication
The following short tutorial takes you through some of the basic steps of developing a Java SE application in the NetBeans IDE. This tutorial assumes you already have some familiarity with developing Java applications. Along the way, you will see some of the IDE’s features that simplify application development.

You will create an application that converts several words into a single word that contains one letter from each of the other words. The resulting word is called an acrostic.

This tutorial takes approximately 30 minutes to complete. If you would like to do a quicker Hello World tutorial, see the NetBeans IDE Java Quick Start Tutorial.

Project Setup
The application you create will contain two projects:

A Java Class Library project, MyLib, in which you will create a utility class.

A Java Application project, MyApp, with a main class that implements a method from the library project’s utility class.

After you create the projects, you will add the library project, MyLib, to the classpath of the application project, MyApp. Then you will code the application. The library project will contain a utility class with a method named acrostic . The method acrostic takes an array of words as a parameter and then generates an acrostic based on those words. The MyApp project will contain a class Main that calls method acrostic and passes the words that are entered as arguments when the application is run.

