# Write That Essay Quiz Auto-completer

### Warnings / disclaimers
This script will usually take four attempts to get 100% on the quiz. If you are not ok with that, do not use this.

### Description
Write That Essay quizzes are parts of the “learning journey” section of the site. This script adds a button next to the “start quiz” button that gets 100% on the quiz. It is very user-friendly.

### Usage
Open Write That Essay, click on “Learning Journey” in the top header (the button is blue and looks like an atom), open the quiz you don’t want to do, press the green button labeled “Auto” and it will do its thing.

### Why it was made
This was made because Write That Essay’s quizzes are the perfect place for me to learn JavaScript and brute forcing. It lets you retry infinite times, it loads fast and it scrambles the answers and questions, adding extra challenge.

### How it works
1. Makes a flexbox and adds the “Auto” button to it, which starts the brute force script
2. Guesses random answers to the quiz, and also records every question and answer’s label
3. Uses the colour of the results page to determine what questions it got right or wrong and checks if it has got 100% (if so, it stops looping) 
4. Saves what questions it got right
5. Guesses the questions again, but makes sure it does not guess answers it has already guessed (using data from step 2) and selects the answers it knows are right (from step 4)
6. Repeats step 3, 4 and 5 until it gets 100% and stops looping
7. 
The challenge with doing this is that the questions are in a different order each time the quiz is attempted. The answers are in a different order too, but both of these just make it more of a fun challenge to make this script work. I will probably never actually use this script, I just wanted to learn some more JavaScript, and I have succeeded in doing that.

### Known issues
- This does not work on the quizzes in the “Story Challenge”
- This sometimes errors if it guesses all of the questions wrong on the first try (very unlikely)

### Updates
This script will not be updated unless people use it and ask me to update it. If you want an update, [add an issue on GitHub](https://github.com/James-Tuppen/Write-That-Essay-Quiz-Completer/issues/new), and I will update it if I get time.