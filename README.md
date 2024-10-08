# ABX-Mock-Exchange-Client


****** Instructions to Run client.cpp on Local Machine ******

## Prerequisites :

- C++ Compiler : Install one if you don't have it.
  - Linux: 
    -Use this command:
    	sudo apt update
    	sudo apt install g++

  - Windows : Install MinGW or Visual Studio.
  - Mac: Install Xcode Command Line Tools.

## Steps to Run the Client:

1. Open Terminal (or Command Prompt on Windows).

2. Go to Your Directory where the "ABX Mock Exchange Client" file extracted:
   cd path/to/your/directory

3. Compile the code with the following command :
   g++ -o client client.cpp -lpthread
   - This creates an executable named "client".

4. Run the node main.js Server (needed for the client to connect):

5. In the same terminal (where you have compiled the client.cpp), run the compiled client:
   ./client

6. Check Logs: Look at "log.txt" in the same directory for messages from the client.

## Important Notes:
- Make sure your firewall allows connections on port 3000.
- Check "log.txt" for any errors if things don’t work.

## Summary:
1. Ensure you have a C++ compiler.
2. Compile your code.
3. Run a server on "127.0.0.1:3000" that is you node main.js file.
4. Execute your client program.
5. Check the log for output.

For any questions, feel free to ask!
