To run the application using your Bluemix account, please follow the steps mentioned below:

1)Click on the Green "Clone or download" button And Download the Zip.

2) Extract the contents into a folder.

3) Please click on the link: https://console.ng.bluemix.net/docs/starters/upload_app.html and Download CF Command Line Interface and install it.

4) Open command Prompt,Set the path to the directory where you've extracted the code.

5)Connect to Cloud Foundry Comand Line Interface using the 'cf' command. set the path to the directory where you've extracted the code.

6)Connect to IBM® Bluemix using 'cf api http://api.ng.bluemix.net'

7)Log in to Bluemix using 'cf login'. Enter your login id and password.

8)If the login is successful , your workspaces will be listed. Select the workspace where you wish to add the project, using 'cf target workspace number from the list' 

9)Run the following command:
cf target -s 'name_of_your_workspace'

10) Push the code using cf push

11) Once the build is completed, go to your bluemix account and check for the project under the specified workspace.

12) Click on the project and check app status. (Upper-right side of the window)

13) If the app is running, click on the link mentioned under 'Routes:' below the app name.

14) If the app status is stopped/unknown, please restart the app and follow step 13)

15) A new tab opens in the browser with the app running.



References:

1) https://console.ng.bluemix.net/docs/starters/upload_app.html

2)https://startbootstrap.com/template-categories/all/




