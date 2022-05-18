# Fourth Assignment

## How to run

This node proyect has use the nodemon and express libraries just to execute the enviroment, using the next command:
#### npm i nodemon express
but, actually you just need to use
####
    npm i

After all node_modules install, you can run the proyect using
####
    npm start
This will run the application.

## How it works

This application uses an Array data structure called ' memory ' to simulate the processes. When the application starts, we initializate the memory, creating many processes. We only create 1/3 of the memory ( 80 KB aprox. ). To create the rows, we use the Math interface to make the data randomly.

After we initializate the memory, we print a table, and we start searching 3 random processes. They're called second by second, and these processes can read, create, write or delete another process, also they can request more memory.

The selection of the operetion that every process is going to execute is choosed randomly too.

Also, the rows are not an Array, they are an object from a class defined on the end of the script.

We use some other functions like isValid( ), print( ) and finishBuffer( ) to make more simple and reusable code.