# Finish-OS-TICKET
Part 3 (Installation)


1.https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6 (We will be using these files to install our Ticketing system) Note: {These are files that are from my class}

2.Search for Control panel-Programs -Turn on and off Windows Features- I nternet Information Services- World Wide Services- Application development features-Then enable CGI APPLY OR INSTALL LET UPDATE


 3. From the Installation Files, look to download and install the file PHP Manager for IIS (From the Installation Files, download, download, accept terms, install, Rewrite Module 

4. Go into files, Click on this PC, Look for C drive open, Double click once inside, Go to new -folder -name it PHP(By clicking on the name you can change it).




![IMG_4396](https://user-images.githubusercontent.com/124942355/218890674-bcf6e60a-bb17-4330-8585-940e30caf6cd.jpg)





5. From the Installation Files, when downloading it may pop up a window with everything inside of it showing ignore that click down load on the right side. PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) when done open file,double click it extract all, find our new folder we created, dump everything inside folder

6. From the Installation Files, look download and install VC_redist.x86.exe their may be more items but ignore it and look too download regardless.

7. From the Installation Files, download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi) {TYPICAL SETUP~ MAKE SURE TO CLICK THE BOX AND INSTALL WIZARD BOX~STANDARD 


CONFIGURATION~Password1} {REMEMBER YOUR INFORMATION}

8. Open ISS as a administration, look for PHP manager, Register new PHP Version. {Restart the ISS, or refresh ISS}
 
 
 
 ![IMG_4393](https://user-images.githubusercontent.com/124942355/218891322-7a1b9d04-d32a-4825-bf1d-622371c992a0.jpg)
[New BETTER.docx]






9. The next step is going into installation files to installing the OS ticket file,then look to drag the upload folder towards the folder inside Files~inetpub~www.root

10. {Go back to IIS refresh or stop and refresh} On the left go to sites click Os ticket then click on the right side browse  80

11. After that’s installed os ticket should have somethings in needs to take care of before it can fully run start by going into PHP again scroll to the bottom until you see enable or disable extension, then look to enable these extensions: Enable: php_imap.dll           Enable: php_intl.dll Enable: php_opcache.dll

12. Then refresh OSticket should notice some red lines are gone but still needs some tweaking hit the continue button head back to files to rename a file that’s located osTicket\include\ost-sampleconfig.php you will be changing too. That files system you can find the file by copying the name putting into the search engine infiles {C:\inetpub\wwwroot\osTicket\include\ost-config.php} 

13. The same file double click or open up the menu for it. Go to properties then to security click advanced remove everyone yes it will be fine to remove all. Then click the add button too add {“EVERYONE” ONLY ALLOW READ AND WRITE}.

14. By now you should be able to fill out the information.Key here is to remember all of your information

15. Lastly you will need a database for your help desk look too download a file in our  Installation Files, named HEIDI, look to install keep hitting next until you have installed it.


![IMG_4395](https://user-images.githubusercontent.com/124942355/218891497-62a47d71-ca29-4191-9103-8f1bd826eb82.jpg)





16. Next step is too add a database for our TICKETING SYSTEM double add new fill out information.

17. When done return back to os scroll to bottom for database username and password fill it out with the information you have used.

18. Then should open up to add tickets but we want too make sure we can login

19. Click on sign in Work here.(  Insert the info you just created for the Ticketing System)


20. Congrats OS Ticketing System Built

![IMG_4393 (1)](https://user-images.githubusercontent.com/124942355/218891558-ba24db49-fa1a-4227-b67f-2c35b8e27c76.jpg)


