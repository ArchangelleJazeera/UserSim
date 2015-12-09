# BRD UserSim
A fork of UserSim that believes in free speech and will post on ShitRedditSays. Praise BRD!

### What is this?

[/u/BRD_User_Simulator](http://www.reddit.com/user/BRD_User_Simulator) is a summonable Reddit bot that reads a particular user's last 1000 comments and uses Markov chains to construct comments in that user's style.

Basically, it pretends to be you. It's what you would write if you were a robot with a nice vocabulary but no understanding of how words should fit together.

### How do I use it?

Summon it like this:

    +/u/BRD_User_Simulator some-user
  
or

    +/u/BRD_User_Simulator /u/some-user
  
if you want that user to get a notification as well.

It's probably running right now; give it a try!

### It didn't work for me. Why not?

It only works on users that have 25 or more comments visible on their userpage, and if the user's comments have little variety (e.g. 25 of the exact same comment), then the bot might not be able to come up with a unique response.

### What libraries does it use?

It uses [markovify](https://github.com/jsvine/markovify), like SubredditSimulator, as well as [NLTK](http://www.nltk.org/) for more coherent responses. Also [PRAW.](https://praw.readthedocs.org/en/v3.1.0/) All the other libraries it uses should be preinstalled with Python.

Like SubredditSimulator, it avoids making comments that are complete and direct quotes of the user. Each comment it makes will be stitched together from at least two of the source user's comments.


### I got a really unfunny reply. This is asenine.

Yeah, it's a bot and it generates its responses randomly; it doesn't know what's funny and what's not. Sometimes its responses are hilariously absurd; other times they're boring and weird and completely unfunny. You're welcome to page it again for a new response if you don't like the last one you got.

-----

If you have any questions or ideas, you can annoy [/u/Trambelus.](https://www.reddit.com/message/compose/?to=trambelus) I guess, though if there are issues with this particular instance running, contact [/u/ArchangelleJazeera.](https://www.reddit.com/message/compose/?to=ArchangelleJazeera)

-----

### Currently banned in NO SUBREDDITS PRAISE BRD
