# Capella-QA-Automation
Steps to install all the Tools/Software for Automation:
1.	Download and Install JDK 8 (Win 64).  Use below link.JDK: http://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html
To verify if JDK is installed successfully open a Command prompt and type "java –version", without quotes.
2.	Download and Install Eclipse Neon (Win 64).  Use below link.
Neon Eclipse: http://www.eclipse.org/downloads/download.php?file=/technology/epp/downloads/release/neon/R/eclipse-java-neon-R-win32-x86_64.zip
2.1	Extract the Eclipse files from the download.
2.2	Copy the files to your local folder.
3.	Download Maven – Binary zip archive.  Use below link.
Maven: https://maven.apache.org/download.cgi
4.	Install Maven using the below steps:
4.1	Ensure JAVA_HOME environment variable is set and points to your JDK installation.
4.2	Extract distribution archive in any directory.
4.3	Add the bin directory of the created directory apache-maven-3.5.0 to the PATH environment variable.
4.4	Confirm with mvn -v in a new shell. The result should look similar to:
5.	Download and Install Github Desktop. Use below link
Github desktop: https://desktop.github.com/
5.1	Login to Github and Sign-in with your credentials.
NOTE: If you don’t have access to the Village Health repository, send email to Sudheer.
5.2	After login go to the Capella-QA-Automation repository.
5.3	Open Eclipse and create a workspace by giving desired path.
5.4	Go back to Github and click on "Clone or Download".
5.5	Click on "Open in Desktop".  The Github desktop client will be opened and display the Eclipse workspace that was created above.
5.6	Once the project is cloned it is defaulted to the Master Branch.  Change the branch to "Develop" using the drop down at the top of the GitHub Desktop client.
6.	Open Eclipse and make sure it is pointing to the workspace we just created above and Click ‘OK’.
6.1	Import the cloned project by clicking on File-->Import-->Maven-->Existing Maven Projects.  Click Next.
6.2	In the root directory click the "Browse" button and browse to the workspace that was created.
6.3	Click Finish.
7.	To Run the project from Eclipse, right click on "CapellaUI" in "Package Explorer" and Select Run As->Maven Test.

