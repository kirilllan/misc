Navigate to your drupal9 folder inside CommandLineInterface.
Create a ".env" file and add the following:
  
  █DBH=db
  █DB=thisisthedb
  █DBU=thisistheuser
  █DBP=thisisthepassword
  
  Now start the container inside the terminal:
█docker-compose up -d
 
Once it is done, you should see the following:
Creating drupal_db             ... done
Creating drupal                   ... done
Creating drupal_db_admin  ... done
 
I would say go ahead and run the following:
chmod 777 -R web/sites/default/files
 
Now go to the Docker Desktop app and click on the drupal9 container. It will take you to the log page and you will see it is downloading and installing stuff. It's gonna get stuck on "Installing drupal/core (9.2.3): Extracting archive" cause it's a heavy file. but just gotta be patient. Then when it is done, go to the localhost:9998. If everything goes well, you should see a login page.

//Summary, ty to L.L.
