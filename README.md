# Web-Development
// Some code that must be included in app.js file everytime
  // At the top

   var express = require('express');
   var app = express();

   app.use(express.static("public")); // Informs express that css and js files to be used are in public directory

   app.set("view engine", "ejs"); // Informs express that ejs files have been used as reponses


// At the bottom
  
   
   app.get("*", function(req, res){
       res.send("Can't understand what you're looking for :/");
    })

    // Telling express to listen for requests(starting the server)

   app.listen(process.env.PORT, process.env.IP, function(){
        // Notifying that server has started  
   console.log("server has started");
    })
