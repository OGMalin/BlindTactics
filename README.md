# BlindTactics
These are tactics file generated from Lichess's tactics with 3 - 7 pieces on the board.
The files are devided in different rating range with a thought fide rating. I used the Dojo's rating conversions. One exercise file and one solution file belong to each range.

I also did run the selection with different score in the popularity (scale -100 - 100).<br/>
<pre>puzzles_all.zip  all puzzles.
puzzles_1.zip    Puzzles with positive scores.
puzzles_50.zip   Puzzles with 50 or more in popularity.
puzzles_75.zip   Puzzles with 75 or more in popularity.
puzzles_90.zip   Puzzles with 90 or more in popularity.
puzzles_100.zip  Puzzles with full score in popularity.

ForPrinting.zip  Sheets for printing in pdf format.
                 These exercises are what I currently are doing.
                 Print it out on a printer that's abel to print on both sides of the sheet
                 and cut each exercises so it would look like a deck of cards.

LichessTacticsConverter.zip
                The program I use to create these puzzles.
                Download the puzzles file from Lichess: https://database.lichess.org/#puzzles
                Then run the program from command line.
                Ex. If you want puzzles with 8 pieces in the range of 2150 to 2224 (Dojo's 1800-1900 Cohort)
                and with the score of 95 or higher, use this command:
                ./LichessTacticsConverter /p 8 /P 8 /r 2150 /R 2224 /s 95 lichess_db_puzzle.csv Exercises.txt Solutions.txt
                Run the program without any parameters to see all options.
</pre>
