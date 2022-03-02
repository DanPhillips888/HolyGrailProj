# HolyGrailProj
full stack exercise for the xPro MIT program

How to Run: 
- Copy files and folders into a common directory on your machine. At the terminal, enter this directory and run npm install for dependancy packages.
- Run a local Docker container with the command: 'docker run -p 6379:6379 --name some-redis -d redis'
- Install redis with the command: 'npm instasll redis' *Note: ioredis rather than the basic redis package was required to run originally. 
- Use the command 'node index.js' to run the local server, then use a browser to navigate to localhost:3000 for the main page and /data for raw database output.
