![](http://www.alsoenergy.com/wp/wp-content/uploads/FullColor_BlackTag-e1413573042293.png)

# Instructions
- You will need Visual Studio 2015 or 2017 to complete challenges outlined below. We suggest you utilize one of the community editions provided at https://www.visualstudio.com/downloads/
- Clone this repo to your local machine
- Use it to create a new repo on GitHub under your own account (please don't use GitHub fork to accomplish this)
- Complete the challenges described below. 
- Send us an email with a link to your repo

## Part 1. Console Application
- Create a console application in Visual Studio
- Create a function to sum up all the even numbers in a supplied List<int> parameter and return the result.
- Create a function that will make a http GET request to a given URL and dump out the result in Console. (Be ready to discuss what external tools you can use to validate the behavior, that your program is indeed making the request for ex: fiddler, wireshark...)  
- Create a function which will print out the numbers in an List<int> to the console in a loop with a configurable delay (print the number out every 500ms, or every 1000ms ). Make sure the function can be called from a thread. In your program create 2 threads, configure your initial thread to print a number out every 500ms, configure your 2nd thread to print out numbers every 1000ms. Your application should block untill all the numbers are printed out to the console.
  
Example output for an input int array of 1,2,3,4,5:
t1: 1
t2: 1
t1: 2
t1: 3
t2: 2
t1: 4
t1: 5
t2: 3
t2: 4
t2: 5
  

## Part 2. Web Application
- Create a secondary application this time start a empty web application (should be under Web\ASP.NET web or Web\ASP.NET Core), add a  http handler to your project and have it simply return the current time (including seconds) to the client when called. Use the debug web server (no need to configure IIS)
- have your console application call the  web application you created in order to receive the current date time and print it in the console window
