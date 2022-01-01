The following file contains the assignment for week 03.

<h3>Given:</h3>

For this assignment, we already gave you some code to start with. This app, Spotify, enables users to add songs to a playlist. 
The code to add songs to the playlist is there but does not have any form of user management. 
Your task is to extend this code by adding a basic form of user management.

1. create a users.json file and structure in a text editor with a few users containing the items below. Take a look at songs.json  
Download songs.jsonfor an example of how to structure such as a JSON file.
  - login name
  - password
  - role ("owner" or "family member")
  
2. Use spotify.py  Download spotify.pyand make the following additions:
  - Make a function that opens users.json
  - Make a function that saves users.json
  - Make a function where a user can log in (hint: look at the code from last week)
  - Make a function where a user with the role "owner" can add a new user with the role "family member". The owner has to be logged in to do this.
  - Make a function where a user can add a song to the playlist. The user has to be logged in. If you are feeling adventurous, 
    you can also add the name of the user that added the song to the playlist as an extra field.
  - Make a function that counts the number of users and prints it
  
The whole "user has to be logged in" can be tricky. A good idea can be to create a variable at the start named "logged_in" with the default value False. 
You can make this True the moment the user logged in. 

Note: while this assignment supports you in the creation and testing of functions, it will not mount up to a working system with an interface where the user can make selections. 
If you are up for the challenge we dare you to create one!
