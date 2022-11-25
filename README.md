# MobileAppSecurityTest
Application Security Lab Group 2 -Test Result (for Alpha Team)

Test Tool Result

1)betterscan-ce:
When we tested the application file with this tool, we did not receive any security threats other than simple clean code warnings, such as empty constructor or unused import. We got an APIKey warning that we thought might be dangerous, maybe it could cause a vulnerability.(Improper Platform Usage)

![Screenshot from 2022-11-25 22-28-13](https://user-images.githubusercontent.com/73425600/204056979-bebe2401-81c7-4eb3-90cc-933c2fc091de.png)

2)Horusec:
We ran this tool directly on the linux terminal and got the same results from the terminal. As a result of the analysis, we got 2 critical and 4 unimportant errors. One of the critical errors was the APIKey error, and the other was the data leak error.

![Screenshot from 2022-11-25 19-18-29](https://user-images.githubusercontent.com/73425600/204057397-c75c47fd-405f-49a1-a78e-cae3d4157de1.png)
![Screenshot from 2022-11-25 19-20-05](https://user-images.githubusercontent.com/73425600/204057386-704edf36-b747-4fab-84d0-941fcc5f56c0.png)

3)Gitleaks:
While using Gitleak, we created a .yml file and checked through the github repository. The following photo shows the result of gitleak. As a result, we did not get any errors with this tool.

![WhatsApp Image 2022-11-25 at 17 48 28](https://user-images.githubusercontent.com/73425600/204057725-be76ac38-c557-418d-ab94-a5ae085b4a2c.png)

4)Mobile Security Framework:
After installing this tool and entering the host link on the terminal, a screen appeared for us to install apk. When we uploaded the apk file that Alfa team sent us, we got a result of the image below. But we were not sure if it was apk file error or project errors.![Screenshot from 2022-11-25 20-04-04](https://user-images.githubusercontent.com/73425600/204057916-5089804c-ad0e-4f10-82da-9aab72bfb646.png)

5)SpotBugs:
We first downloaded this tool as zip and then uploaded its plugins to android studio. When we started analysis on the code of friends, it could not find the class file, so a bug was not found. Nor did we see any threats.

 file:///home/amine/Downloads/WhatSie/WhatsApp%20Image%202022-11-25%20at%2021.41.31.png
 
 6)SonarQube SCA:
After installing this tool, we pushed the project on SonarQube's homepage and it was detected as gitleak as a result of the analysis. That's why we didn't get the result. Afterwards, we tried SonarCloud with the same method, and as a result, we did not receive any threat or error in the project.

 file:///home/amine/Downloads/WhatSie/WhatsApp%20Image%202022-11-25%20at%2022.12.49.png
 
7)automated-security-helper & Fluid Attack’s Scanner:
We constantly got a terminal error while installing these two tools and unfortunately we couldn't solve it no matter how hard we tried. We couldn't find the ash file for automated-security-helper, and we couldn't run terminal commands starting with m for Fluid Attack's Scanner.

Nükte Özkılınç ER1328
Amine Ceyda TAndoğan ER1329
