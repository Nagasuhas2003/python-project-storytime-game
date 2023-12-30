# python-project-storytime-game
It's fun terminal game which gives different stories based on your input .so to try giving random words and enjoy the story
code explanation
he code starts by opening a text file called "story.txt" and reading in the contents of that file into a variable called story.
The code then loops through all the characters in the string, which is done using an enumerate function.
For each character, if it's between target_start and target_end, then start_of-word will be set to that index value (i).
If it's not between those two values, then word will be set to whatever comes after target_start + word + target_end (which excludes those three characters) and words will be updated with this new word.
The next part of the loop is where we ask for input from the user on what they want us to replace every instance of "target start" with.
We do this by creating a list called answers and putting them inside our list of words so that when we iterate over all our words again later on, we can use these as replacements instead of just replacing everything with "target end".
The code is used to replace the words in a text file with their corresponding answers.
