
edwinwallis.com


You have a web sever with Bluehost for the next 36 months (2020).  One of my regrets of college is not getting 'dirty' earlier.  Obviously the webspace is not the only area of Computer Science that exists.  It's just one that has captivated me.
If I could give myself something when I was your age it would be this.  What is 'this?' its a short guide on how to get set up with you website.  This website is 100% yours, you can do whatever you want with it.  What is whatever?  The web sever that you have
has database access using PHP/MySQL.  You can also of couse upload html, css, and javascript files.  You don't have to do any of this stuff, but every good computer science person needs a website...
  
How do you get these files from github to your computer?  First you need to sign up for a github account.  If you don't have an account already you will have to make one by the end your time at RPI.  It's what pretty much
everyone uses to store there code (Like google docs for code). An import distinction: GitHub is the company that hosts the code.  'Git' is the software that you use.

You can download Git here: https://git-scm.com/download/mac.

Once you have a GitHub account all set up (https://help.github.com/articles/set-up-git/). Go to where you want to download the files in terminal.
And type 'git clone https://github.com/wwallisabc/Web-Sever.git' This will download the files to your computer.


// ------ Your Account ------ //

Once you login into BlueHost you will see a bunch of stuff - ill let you explore. 

How to I upload files?  One of the ways is to use something called FTP (File Transfer Protocol).  In order to use this
Protocol you have to download a FTP client AKA an application which allows you to use FTP.  The one I use is called
Cyberduck (https://cyberduck.io/).  

Once you open Cyberduck click on Open connection.  Make sure the top option is set to FTP.  To get the details of how to configure FTP
Client log on to bluehost.  Click FTP in the top menu, then scroll down to 'FTP Accounts' section.  With the one called edwin@edwinwallis.com click 
 configure FTP client and it will show you what to put in the different sections.
 
// ---- Database Stuff ----- //

If you go to http://edwinwallis.com/Edwin.php

It go into the database to displays it pretty simply.

In order to see how the database works login into bluehost, click cpanel, then find phpMyAdmin under the database tools option.

Then once it loads looked under the phpMyAdmin logo and you will find 'edwinwal_testOne.' Expand it then click on books.  And that is a table in a databases.  The interface is so its easy to play with it.  You can do all this by the command line but this is easier for know.