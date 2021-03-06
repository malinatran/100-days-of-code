# 100 Days Of Code - Log

### Day 0: January 03, 2017
**Today's Progress:** Created a program to find all anagrams of a word.
**Thoughts:** This was fun! I learned new things, like that a `word` file exists on my (everyone's) computer and how to use the terminal to find a document (`find / -name "word"`). Struggled with figuring out best way to sort through file and type of data structure to store words of the same anagram.
**Link:** [Anagram finder](https://gist.github.com/malinatran/40ace5a3286693105bb59248ea381f43)

### Day 1: January 04, 2017
**Today's Progress:** Worked on a few code challenges from FreeCodeCamp.
**Thoughts:** Although the challenges were progressively more difficult, I found it easier once I was in a certain frame of mind. My default is to create an array, iterate through args, and push to that array (lol). Learned that you can create RegExp objects in JavaScript and `.match` will return either an array or `null`, but you can wrap it around a `Boolean` object to get a boolean. I chose to refactor the Confirm Ending exercise because I knew the code was satisfying the existing tests but wasn't living up to the spirit and purpose of the challenge. Got to do some more regexin'.
**Links:** 
- [Find the length of the longest word](https://gist.github.com/malinatran/d77cb690f84c32cfe06991772c5d850e)
- [Title case a sentence](https://gist.github.com/malinatran/2becb9579f4e5dfbfa3bed30e0e2f0ce)
- [Find the largest number in subarray](https://gist.github.com/malinatran/49630c40fbd2ac405960b70b7bbb314c)
- [Confirm ending of word or sentence](https://gist.github.com/malinatran/cdaccd2f9b4a40a1db993e4efa190a24)

### Day 2: January 05, 2017
**Today's Progress:** Worked on my hosted tic-tac-toe game.
**Thoughts:** I really wanted to probe and see if I can make my game playable for two players. And guess what? I could! I set up another endpoint for two players and abstracted logic related to the game state. Users can click on the "2 Players" button and an Ajax request will hit the endpoint. It's less involved on the server side since the only logic my server will check for is whether the game has ended and if so, whether there is a winner. In terms of the UI, I'm storing the current player's marker and switching between the two.
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 3: January 06, 2017
**Today's Progress:** Worked on my hosted tic-tac-toe game.
**Thoughts:** I wanted to refactor my code and streamline the server's responsibility. What this means is that I wanted to hit the same endpoint (`/make_move`) no mattter if it's a single-player or two-player game. It was not too complex, but I was thrown off by one UI issue (the message board not being updated) and realizing that I needed to change the value passed to the server into a boolean, as opposed to "true" or "false" (string values).
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 4: January 07, 2017
**Today's Progress:** Worked on my hosted tic-tac-toe game.
**Thoughts:** Didn't make much headway, except I migrated tests and added more test coverage to the `/make_move` endpoint. Explored an issue that I was having with receiving and responding to requests for the favicon. Still confused. 🤔
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 5: January 08, 2017
**Today's Progress:** Worked on my hosted tic-tac-toe game.
**Thoughts:** More test coverage! Fixed a bug that occurred when playing a two-player game followed by plyaing a one-player game (the human player's marker was then X, not O). Spent only 40 min coding, but I think it's fair since I've been coding for 2 hrs+ on the other days. 
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 6: January 09, 2017
**Today's Progress:** Worked on a few code challenges from FreeCodeCamp.
**Thoughts:** I got about a decent half-hour in after attending an evening event, but for the sake of sleep, I'm wrapping it up.
**Link:** [Repeat string num times](https://gist.github.com/malinatran/5af72e5eb3ac2bca2a08f440188b7b25) and [truncate string](https://gist.github.com/malinatran/474753ee5f241938d955013f16463674)

### Day 7: January 10, 2017
**Today's Progress:** Debugged hosted tic-tac-toe game.
**Thoughts:** I was having major issues and after hours of exploring the source of these issues, realized that it was due to how I was storing a global variable. Another issue was a result of not properly translating a value of `nil` into a string. Sending a `nil` vlaue ends up just being blank. So many lessons learned, many hours later.
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 8: January 11, 2017
**Today's Progress:** Debugged hosted tic-tac-toe game.
**Thoughts:** Fixed issue with shared state. 
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 9: January 13, 2017
**Today's Progress:** Git && looking into Selenium webdriver.
**Thoughts:** Tried to fix an old git message and wasn't able to rebase it without having merge conflics. This sent me a wild goose chase, and I still haven't been able to resolve. 
**Link:** None!

### Day 10: January 14, 2017
**Today's Progress:** Fix integration tests
**Thoughts:** Having made changes to how my app operates, the integration tests necessitated changing as well ☺️
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)

### Day 11: January 15, 2017
**Today's Progress:** Refactor integration tests
**Thoughts:** I re-wrote a Gherkin statement and implemented a step definition that is indicative of a two-player game. Originally, I just checked that I could see a 3x3 board being rendered but also wanted to demonstrated that as the user of a 2-player game with a marker of 'X', the user would be able to make the first move. I also worked on creating a linked list class in JavaScript, which was a tough but helpful exercise in thinking about basic data structures. 
**Link:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server) and [linked list](https://gist.github.com/malinatran/18c03114d833527d1cacf1d0b6cce4ce)

### Day 12: January 16, 2017
**Today's Progress:** Continued linked list exercise
**Thoughts:** Added `remove` method!
**Link:** Will share later! #lazy

### Day 13: January 22, 2017
**Today's Progress:** Reading about Big O notation, simple & binary search, arrays & linked lists in "Grokking Algorithms"
**Thoughts:** Have I really not done anything in 6 days? 😱 I started reading this book, which is really accessible, easy-to-read, and visual-heavy. All of the code is written in Python, which I've translated into Ruby just to make sure I understand them. There are also exercises which I've been following along.
**Link:** 
- [Binary search algorithm](https://gist.github.com/malinatran/65f56ed9d81a272c0ca58d7d7def571f)
- [Selection sort](https://gist.github.com/malinatran/68486a0c6ce5c4511ae455eeab0a0660)

### Day 14: January 27, 2017
**Today's Progress:** Revisited an old Rails project
**Thoughts:** Just working on this for funsies. Decided to fix commit messages, remove year (whoa, 2015!), and make the icons on the dashboard clickable, and fixed some styling issue that resulted from that.
**Link:** [dataDiary](https://github.com/malinatran/datadiary)

###  Day 15: January 28, 2017
**Today's Progress:** Worked on a challenge that requires flattening, normalizing, sorting, removing duplicates of an array
**Thoughts:** Just working on this for funsies. Flattening (without using the `flatten` method) took me the longest time (oh recursion). I also learned about pretty printer in Ruby. 
**Link:** [Challenge](https://gist.github.com/malinatran/d870087530884d1b81629fca1295f64e)
