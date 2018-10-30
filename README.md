# Here-maps
location tracker and login app 

The web app uses geo location to display user's current location using here maps.
the data of user's location is stored in database every 10 sec.this data is used
to generate a report and display the whole route taken by the user in the map 
according to the time stamp assigned.

#Setting-up

1. open mysql command line client and login by entering your mysql password
2. open the "Database.txt" file and paste the whole code into mysql command 
   line client.(Remember to press "enter" in the end).
3. open "sql_connection.js" file ,replace password in line 6 with your mysql password.
4. open command prompt.(start->cmd->press enter)
5. Go to the folder in which the files are saved.
6. write "nodemon startcopy.js".
7. cmd should display "server up at 1000,sql connected". means everything is running good.
8. Open web browser and visit link "localhost:1000".


#Usage

1. on visiting "localhost:1000" login/signup page should displayed.
2. click on "Goto map" in navigation bar to see map with your current location marked as "H"
3. Click on login you will be directed back to index page.
4. Now create a new account by providing all the required details for account creation.
5. now login using the same credentials.
6. After logging in click on <yourname>'s location button. you will be directed again to map page.
  but this time your position co-ordinates would be stored in the database every 10 sec.
7. clicking on "report" in the navigation bar wil direct you to another map which display a whole 
   route of places you have visited SORTED ACCORDING TO TIME STAMP.
8. Now visit the profile page again by adding credentials and click on edit button.
9. Here your current details are displayed. you can make changes in them or upload new photos also.
9. Clicking on logout will log you out and destroy browser's cookies.
10. your details are permanently stored in database and you can login again whenever you want.
  
  
  
  #Thank-You-For-Visiting
