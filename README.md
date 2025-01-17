# Setting up the Demo Environment
This is a simple document detailing to setup Coding Mistakes that Hackers Abuse training demo applications. You can follow these instructions in order to setup your environment and run demo applications by yourself.

# Requirements
Demo applications are implemented in CSharp (16) and Java (2). Visual Studio Community 2019 and Spring Tool Suite 4 are the choice of IDEs. 

<table>
  <tr>
    <td><img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019.png" width="300px" /></td>
    <td><img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4.png" width="300px" /></td>
  </tr>
</table>

# Importing CSharp Applications

Here's a simple example on how to import .NET applications into your VS environment. 

<p>First click on "Clone or check out code".</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019_1.png" width="450px" />

<p>Then, enter the related repository's location and select a local path. Here BuggyExtensionCheck application is used as an example.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019_2.png" width="450px" />

<p>After the import, open it using File->Open->Project/Solution.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019_3.png" width="450px" />

<p>Choose the local path given when importing the repository above.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019_4.png" width="450px" />

<p>Build and run the project.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/VS2019_5.png" width="450px" />

# Importing Java Applications

Here's a simple example on how to import Java applications into your STS environment. 

<p>First select or create a new workspace.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_1.png" width="450px" />

<p>Click on Import projects...</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_2.png" width="450px" />

<p>Type git and select Projects from Git, click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_3.png" width="450px" />

<p>Select Clone URI, click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_4.png" width="450px" />

<p>Fill the details, such as Git repository URL (credentials shouldn't be necessary). Here AutoBindBlacklistByPass application is used as an example. Click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_5.png" width="450px" />

<p>Select master as the branch, click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_6.png" width="450px" />

<p>Choose a local destination, click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_7.png" width="450px" />

<p>Select "Import existing Eclipse projects", then click Next.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_8.png" width="450px" />

<p>Click Finish.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_9.png" width="450px" />

<p>Make sure the project is selected and click Finish.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_10.png" width="450px" />

<p>In order to run the demo, select Run->Run As->Spring Boot App. Then enter the http://localhost:8080 into your browser.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_11.png" width="450px" />

<p>In case there are build errors, please update the pom.xml by right clicking the project and Maven->Update Project.</p>
<img src="https://github.com/codingmistakes/setup_environment/blob/master/STS4_12.png" width="450px" />
