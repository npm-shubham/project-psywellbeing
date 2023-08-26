# project-psywellbeing
Create and open the folder where you want to create the project. 

Right-click anywhere in the folder, click on ```Open with Code``` and open the terminal.

Enter the listed commands: 
~~~
npm init
~~~
> Specify the required details that will be asked and press ```Enter```
~~~
npm install mongodb
~~~
> Press ```Enter```
~~~
npm install -g nodemon
~~~
> Press ```Enter```
> There is a high chance that it will show you ```ExecutionPolicy``` error
> To fix this open PowerShell as Administrator, and enter the following commands
> ~~~
> Set-ExecutionPolicy Unrestricted
> ~~~
> Enter ```Y``` and press ```Enter```

Now you can see that the folder ```node_modules```, ```package.json``` and ```package.json``` files are created.
Now copy the downloaded files i.e., src and index.js files into the folder you made. 
In the terminal, enter the following to make the project live.
~~~
nodemon
~~~
> It will run on ```http://localhost:6969/```

### Note: Make sure to update the Mongodb database key with your own key.
