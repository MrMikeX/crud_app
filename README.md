# crud_app
I made a simple CRUD app in Visual Studio Code based on Nodejs, Express and MySQL.
To Run the crud app you need to install the following packages on server folder:
1. cors (**npm install cors**) 
2. dotenv (**npm install dotenv**)  
3. express (**npm install express**) 
4. mysql (**npm install mysql**)

The **dotenv** module is needed to store the configuration for the database (ex. username,password,port).

# Setup the Database

1. For my setup I used the XAMPP software. All you need to do is to run __Apache__ and  __MySQL__ module:

![GitHub Logo](/images/xampp.PNG)


2. Then, you need to open __phpadmin__ and  import the database __crud_app.sql__.

3. Create an new user (username & password) on phpadmin (_or use someone that already exists_). <br />

![GitHub Logo](/images/user.png)

4. Create the .env file in the server folder by importing the following: <br />

PORT=5000 <br />
USER=__yourname__ (_the username that you added on step 3_) <br />
PASSWORD=__yourpass__ (_the password that you added on step 3_) <br />
DATABASE=crud_app <br />
DB_PORT=__3325__ (_or the port that your server is running on_) <br />
HOST=localhost <br />


# Run the code

After you have imported the project into Visual Studio Code and have installed the modules, you can install nodemov or the "Live Server" extension, which they are updating your server in real time. Create a terminal on server folder and run the crud app by typing "__node app__" or "__nodemov app__". If you use node without auto-updating you need to press right click and activate the Live Server Extension on VS Code.

An example of view:

![GitHub Log](/images/example_view.png)

