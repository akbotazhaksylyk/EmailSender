1) Unzip the zip file and run the folder in your tool (I'm using Visual Studio)

2) Launch a terminal and write there "npm install express path nodemailer"

3) Look at the code under the comment "//Create Nodemailer transporter" in the app.js file. In the "user:" line, 
enter your email address and in the "pass:" line, enter your application password (Google Settings -> Security -> App password)

4) Write to the terminal "nodemon app.js" to run the program.

5) Go to any browser and write localhost:3000 and you can safely send an email!