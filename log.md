# 100 Days Of Code - Log

### Day 0: January 03, 2016

**Today's Progress:** Created a program to find all anagrams of a word.

**Thoughts:** This was fun! I learned new things, like that a `word` file exists on my (everyone's) computer and how to use the terminal to find a document (`find / -name "word"`). Struggled with figuring out best way to sort through file and type of data structure to store words of the same anagram.

**Link:** [Anagram finder](https://gist.github.com/malinatran/40ace5a3286693105bb59248ea381f43)

### Day 1: January 04, 2016

**Today's Progress:** Worked on a few code challenges from FreeCodeCamp.

**Thoughts:** Although the challenges were progressively more difficult, I found it easier once I was in a certain frame of mind. My default is to create an array, iterate through args, and push to that array (lol). Learned that you can create RegExp objects in JavaScript and `.match` will return either an array or `null`, but you can wrap it around a `Boolean` object to get a boolean. I chose to refactor the Confirm Ending exercise because I knew the code was satisfying the existing tests but wasn't living up to the spirit and purpose of the challenge. Got to do some more regexin'.

**Links:** 
- [Find the length of the longest word](https://gist.github.com/malinatran/d77cb690f84c32cfe06991772c5d850e)
- [Title case a sentence](https://gist.github.com/malinatran/2becb9579f4e5dfbfa3bed30e0e2f0ce)
- [Find the largest number in subarray](https://gist.github.com/malinatran/49630c40fbd2ac405960b70b7bbb314c)
- [Confirm ending of word or sentence](https://gist.github.com/malinatran/cdaccd2f9b4a40a1db993e4efa190a24)


### Day 1: January 05, 2016

**Today's Progress:** Worked on my hosted tic-tac-toe game.

**Thoughts:** I really wanted to probe and see if I can make my game playable for two players. And guess what? I could! I set up another endpoint for two players and abstracted logic related to the game state. Users can click on the "2 Players" button and an Ajax request will hit the endpoint. It's less involved on the server side since the only logic my server will check for is whether the game has ended and if so, whether there is a winner. In terms of the UI, I'm storing the current player's marker and switching between the two.

**Links:** [Hosted TTT](https://github.com/malinatran/tic-tac-toe-x-web-server)
