# roombots_meetup_instructions

Tonight We're going to be writing javascript to control roombots. :robot_face:  This will help get you up and running. 

### Clone down the Repos 

There is a node based repo and a browser based repo. In these instructions I'll be referencing the node version, but both are pretty similar. Clone down the repo of your choice. If you use the node version, make sure you have node installed on your machine.

Node Repo: https://github.com/paniclater/node_roombot

Browser: https://github.com/mmmries/browser_roombot

Open up the repo in your favorite editor. 

### Navigate to the Simulator

The simulator is where you'll practice connecting to and controlling the roombot. Select the simulator of your choice: http://roombots.riesd.com/simulations

### Connect your app to the simulator

If you're using the Node Repo, run `npm install`. Copy and paste the IP and channel from the simulator to your app. See the screenshot below for example of where to find the channel and IP. 

![simulator channel and ip](https://raw.githubusercontent.com/lukeschunk/roombots_meetup_instructions/master/Screen%20Shot%202016-05-05%20at%209.51.51%20AM.png)



##### Once you copy and paste the channel and IP into `app.js` (for the browser based repo it will be `index.html`), you should have something that looks like this: 



![App Example](https://raw.githubusercontent.com/lukeschunk/roombots_meetup_instructions/master/Screen%20Shot%202016-05-05%20at%209.51.27%20AM.png)


### Run the App 

You should be ready to run the app and connect to the simulator. For the node app, run `node app.js` in your CLI. You should see two messages: `WebSocket Client Connected` and `Heart Beating`. If you see those messages, check out the simulator. The Roombot will be spinning in a circle. It's alive!

### You're Good to Go 

Start experimenting by responding to messages from your Roombot simulator's sensors, and sending it different types of drive messages. 

If you want to check out more about the Roombots, you can check out the official docs: http://roombots.mx.com/ 
