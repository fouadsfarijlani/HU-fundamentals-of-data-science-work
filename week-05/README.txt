
The following file contains the assignment for week 05.

Given: 

Part 1: Chuck Norris promptly killed Video for killing the Radio Star.

Chuck Norris facts are satirical factoids about martial artist and actor Chuck Norris that have become an Internet phenomenon and as a result, 
have become widespread in popular culture.
The 'facts' are normally absurd hyperbolic claims about Norris' toughness, attitude, virility, sophistication, and masculinity.
Not surprisingly, Chuck also has an API dedicated to these facts: chucknorris.io. For the first part of this assignment, you are going to retrieve data from this API.

1- Check out the documentation on https://api.chucknorris.io/ (Links to an external site.) and read how to address the “random chuck joke” endpoint works.
2- Create norris_random.py and write code that retrieves a random chuck joke and prints it on the screen
3- Now check the documentation on https://api.chucknorris.io/ (Links to an external site.) and read how the “free text search” endpoint works.
4- Create norris_search.py and write code where the user searches with a query and returns jokes based on that query. 
   This will, of course, return more than one joke so a for-loop is in place.
   
Part 2: Do or do not. There is no try.

Who doesn’t know Yoda, the fictional character from the Star Wars universe? In the most recent Star Wars series, 
The Mandalorian, there is even a baby Yoda. Yoda has become iconic in popular culture due to his distinct pattern of spe­ech and role as an old, wise mentor. 
The title of this part refers to that. Just like Chuck Norris, Yoda has his own API.

  1- Check out the documentation on https://github.com/richchurcher/yoda-api (Links to an external site.) how to turn a normal text string into Yodish
  2- Create talk_yoda_to_me.py and write code where the user is asked to submit a sentence. This sentence will be transformed into Yodish using the API. 
      Print this new sentence.
    
Part 3 (extra challenge): Chuck Yoda!

Now we know how to address both APIs it is time to connect them into our new service. Chuck Yoda.

  1- Check out the documentation on https://api.chucknorris.io/ (Links to an external site.) and read how the “random chuck joke from a specific category” endpoint works.
  2- Create chuck_yoda.py and write code that
    2a- Take a random Chuck Norris quote from the science category.
    2b- Change the text “Chuck Norris” with the replace method to I or I am.
    
