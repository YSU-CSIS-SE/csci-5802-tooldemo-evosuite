## EvoSuite

EvoSuite is a tool for automatically generating regression unit tests for Java software packages. It can be used with eclipse, maven, and intellij as a plugin or it can be simply be used from the command line.

Setup: For each of the IDE there is a download that allows it to be used as a plugin. For intellij you go to the preference panel and go to plugins where evosuite plugin is found under unit testing. For maven you must configure the pom.xml of the project you wish to use it with and add to it. Eclipse is downloaded from an eclipse update site or if you are using jenkins then there is a seperate plugin. Command line is comes as an executable jar file java -jar evosuite.jar <options>.

Run: To run evosuite for each system is quite different but can be easy. For maven once you are done configuring then run the project. Intellij you simpy go to project and pick run evosuite. Eclipse . And for the command line use the command java -jar evosuite.jar <target> [options] with target can be a class,class path entry or package prefix.

Use: As mentioned above evosuite is used for making junit 4 tests and is setup before running the program.

Evaluation: Easy to learn - It is pretty easy to learn since there are multiple tutorials for evosuite so it scores pretty well here.
            Platforms - Including the use of command line it has a total of 4 platforms to perform with which is pretty good but there  are still systems that do not use it.
            Usage - Evosuite is limited to only being used in Java and even then it is limited on what it is used on but still it does what it is supposed to.

For more information visit http://www.evosuite.org/evosuite/
