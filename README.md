name : hello wrold
 
  
  on:
  
     push:
     
       branches:[main]
jobs:

demos:

runs on : ubuntu-latest
   steps :
     -name : Greetings
        run : echo "hello world"
