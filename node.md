 Comeing over form the Blog_mobile applicaiton

 we want to create and End point to querey for later.

In the Package.json 
 we add in scripst
  
 "db": "json-server -w db.json",
    "tunnel": "ngrok http 3000"

    to start the Server with Json and what Port we want to show to the world. 

     we run 
     "npm run db"
       in the terminal to run our server.

    Then in another Window... I will run 
    "NPM run turnnel"
    
    Make the terminal avabile to the outside world. then we can assess that JSon anywere in the world. 