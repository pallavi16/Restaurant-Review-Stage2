# Restaurant-Review-Stage2
### Part 2: Connecting the fully responsive, mobile-ready Restaurant review application from part 1 to an external server

### Overview:
In Stage Two of Restaurant-Review Application, we utilizwe the fully-responsive, mobile-ready application from Part1 and connect it to an external development server. To begin with, the application uses asynchronous Javascript to fetch/ request JSON data (located in the other repo) from the server. This received data is stored in an offline database using IndexedDB architecture.
Later, the data along with the application are optimized to achieve performance benchmarks (which are tested using Lighthouse).

## Installing and running the development server
Download the server from https://github.com/udacity/mws-restaurant-stage-2.
You can either use command line to clone the repo using 'git clone URL' or you can download the zip folder given in the server repo.
To run the server, make sure that you have node, npm , sails installed on your machine.
Now, start the server by running *node server* from root folder.
By default, the port is set to 1337 and can be run on http://localhost:1337. However, the port can be changed if needed.

## Running the application
To run the application, first of all, clone this repo.
- Using Terminal enter into project directory
- In the terminal, check the version of Python you have: python -V.
- To run it with either of the Python versions:
  - If you have Python 2.x, spin up the server with "python -m SimpleHTTPServer 3000" (or some other port, if port 3000 is already in use.)
  - For Python 3.x, you can use python -m http.server 3000
- With your server running, visit the site: http://localhost:3000


To debug/test the code, Chrome DevTools serve the purpose in the Browser Inspector. You will also see a message in the console "Service worked registered" to show that the app is running successfully
