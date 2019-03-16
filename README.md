# FCC-Request-Header-Parser
This project was coded as part of the FreeCodeCamp Apis and Microservices Projects - Request Header Parser. You can also try it out here:

## To use this:
1. Ensure you have node.js installed. If not install from https://nodejs.org/en/
2. Clone/download this repo
3. (Skip this if you used git clone) Unzip the downloaded file. 
4. Open command prompt (for windows, win + r -> cmd -> enter)
5. Change directory into the FCC-Request-Header-Parser folder
6. If you do not have express and cors, run the following commands: npm install express, npm install cors
7. Run the command Node server.js, you should get a reply of "Your app is listening on port 50023" (50023 is the port i specified to listen on, NOTE: if you want to dynamically assign ports, change the codes in the server.js file from app.listen(50023... to app.listen(process.env.PORT... )
8. Now go your localhost with the assigned port, 127.0.0.1:50023 and refer to that for usages

# If you want to try doing this project:
You can either visit http://freecodecamp.com
OR
Clone the base Repo from FCC: https://github.com/freeCodeCamp/boilerplate-project-headerparser/
and Ensure that you meet the User Story below:

# User Story:
1. I can get the IP address, preferred languages (from header Accept-Language) and system infos (from header User-Agent) for my device.
