# SUNK-MAN

This is a fun twist to the ubiquitous word guessing game "Hang-man". It was inspired by a small "blooper" while serving in the army, where
a Humvee sunk in quicksands (ups!). It also pays homage to my cherished Sergeant at the time. If you know how to play Han-gman, you already
know now how to play Sunk-man; since the rules from the classic game remain unchanged. Nonethless, below are the rules of Hang-man in the 
context of Sunk-man

- A player tries to guess (guesser) a word of chice from another player (riddler), which will remain hidden. The riddler also specifies the number of
attempts allowed.
- As many blank spaces as the number of letters in the word of choice will be drawn.
- The guesser proceeds to take guesses to frigure out the hidden word. A guess can be either a whole word or a single letter.
- If the word/letter guessed is incorrect (meaning the word guessed does not match the hidden word for a word attempt or the letter guessed is not contained
in the hidden word for a single letter attempt), the Humvee sinks by one level (i.e an attempt is dedacted).
- Coversly, if the word guessed is correct the game ends and guesser wins. If the letter guessed is contained in the hidden word, the black spaces will
be filled with that letter at the correct location. The guesser then can continue making guesses and NO attempt is deducted.
- Attempts are only deducted if the guesser makes an incorrect guess.
- The game ends either if the guesser reveals the hidden word before running out of attempts (i.e guesser wins and the Humvee is winched out the sand by a Record)
or if the guesser runs out of attempts to continue guessing (i.e guesser loses and the Humvee sinks completely).
- If guesser runs out of attempts, the word that he/she was trying to guess will be diplayed for his knowledge. 
<br>

# Version 1.0 
The objective of this version is to be able to implement a computer version of Sunk-man with all the classic rules of Hang-man WITHOUT ANY 
modifications whatsoever. The programming language of choice is Pyhton. Words will require user input at the moment, but further updates can
make it possible for the script to randomly choose a word, and even entire phrases, for the user to guess. Graphics for this version will be
rudimentary, but again, future updates can incoporate better graphics.
