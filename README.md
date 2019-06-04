<h1>Gekko Google App Deployable</h1> 

This repository is the fork of <a href='https://github.com/askmike/gekko'>this repository.</a>
I just modified it to work with google app engine which can help you to run the <a href='https://github.com/askmike/gekko'>Gekko</a> trading bot 24/7 without allocating a special device for trading using this bot.
Feel free to use this trading bot with Google Cloud thus maximising the profits.
<br>
<strong>Installation</strong>:<br>
Step 1: Create a <a href='cloud.google.com'>Google Cloud</a> account.(At the time of writing this README Google provides free access to cloud platform. So feel free to play around it.)<br>
Step 2: Create a <a href="console.cloud.google.com/projectcreate">project</a>.<br>
Step 3: Create an <a href='https://cloud.google.com/appengine/docs/standard/go/building-app/creating-your-application'>Application Engine</a><br>
Step 4: Download and install the <a href='https://cloud.google.com/appengine/docs/standard/go/download'>Google Cloud SDK<a><br>
Step 5: Clone or download this repository to a folder in your file.
  <br>Use Command: git clone https://github.com/pranav3714/gekko-1.git<br>
 Step 6: Run command: cd gekko-1 && npm install && cd exchange && npm install && cd ..<br>
 Step 7: Run cammand: gcloud init <br>
 Step 8: The gcloud will ask some questions just answer them and authorise login to your Google account registered with Google Cloud.<br>
  Step 9: Run command: gcloud app deploy<br>
 <strong>Additional Information</strong><br>
 To manage the setting of your tradebot you can use the config.js file present in this repository.<br>
 I was not able to make the UI of this bot work and I don't recommend activating it due to security reasons.<br>
 You can create and deploy your own strategies or that you get from the Internet by making changes to the strategies folder.<br>
 For additional info <a href='https://gekko.wizb.it/docs/introduction/about_gekko.html'>visit here</a>.
 <br><strong>Feature </strong>
 <br>Pre-integrated with two most profitable strategies I have seen till now.(neuralnet, neuralnet_v2, DynBuySell)
  
