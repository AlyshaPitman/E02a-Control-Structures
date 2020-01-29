
# E02a-Control-Structures

Edit README.md to answer the following questions:

- Open main01.py. Before running it, what do you expect this program to do?
# I expect main01.py to begin with "Greetings" upon opening the file in Python, and then ask me what my favorite color is when I hit the enter key
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
# It occurs to me that I am bad at reading with precision. It began with "Greetings" automitcally, and without any further input, asked "What is my favorite color?" 
  - What do you think the program did with what you typed in answer to the question?
# It might have stored that information temporarily, but it appears to have done nothing
- Open main02.py. Before running it, describe how this is different than main01.py.
# It has an extra line of command prompt and a different layout which appears to have been set up to perform the following-
  - What do you think the color = input() will do?
# I think this program will behave much in the same way as main01.py, except once it has asked "what is my favorite color" it will follow up with my previously inputed response 
  - Run the program in the terminal and answer the question. Did the program do what you expected?
# Instead of automatically responding with the color I had entered in the previous program, it waited for me to input a response, and then reiterated that response back to me.
- Open main03.py. Before running it, describe how this is different than main02.py.
# This program is similar to the previous two, although it differs in that it is set up to guess what your favorite color is, and readjust its guesses in accordance to your response. 
  - What is happening on lines 9–12?
# This is the part of the code which tells the program to guess what the color is, and keep guessing if the player's response is not "correct"
  - Why are lines 10 and 12 indented?
# They are like branches or "if this - then this" code segments 
  - Run the program and answer the question. What happens if you don’t capitalize Red?
# It freezes for a while, and then sends back an error message telling you it cannot recognize the function
  - What does this tell you about "color"?
# It tells me that unless there was an extra line of coding allowing for "red" to be an acceptable answer, it would continue to only accept the capitalized version
- Open main04.py. Before running it, describe how this is different than main03.py.
# Response dialogue is set up in a slightly different way here, but more importantly, the program is set up to allow both "Red" and "red" as appropriate responses
  - What problem is this trying to solve?
# As stated previously, in the former program, it would only allow a specifically capitalized "Red" as a response to the question "What is my favorite color," players who don't think to be initially gramatically correct in attempting to play this game would be subject to this potential blip.
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
# Funnily enough, even though it was not covered in the programming set up, when I input "rED" it only responded with "Sorry, try again." When I tried "RED" it sent back an error message. After I attempted to answer correctly, it still sent back error messages. I had to restart the program to fix it after I recieved the error message. 
- Open main05.py. What do you expect line 9 to do?
# I'm not actually sure what this line does as it's the first time I've seen anything like it. 
  - What problem is it trying to solve?
# Contextually, I would say it allows for any capitalization variant on the word "red."
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
# This program is pretty bare-bones and finicky, it's difficult to get things just right with it. It did accept any capitilzation variant. After I tried adding spaces, it sent me one "Sorry, try again," and then proceeded to send me only error messages with any other attempts.
 - Open main06.py. How is line 9 different than in main05.py?
# The only discernible difference between line 9 in main05 and main06 is the word "strip" inserted in main06
   - What would you guess .strip() is doing?
# I really have no idea what "strip" would trigger. I would figure it would work in the same manner as a subtraction sign. 
   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
# It appears that the "strip" prompt allowed for the program to recognize "red" even with inserted spaces, although inserting other special characters or mispelling the word will still break the program.
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
 # This program has a new option branch inserted so that if the player guesses the word "pink" the program will respond telling them they were close to the answer.
   - What is happening on line 12?
# Line 12 tells the program to recognize the new input possibility of "pink"
   - Run the program and answer the question.
# I can run the program and enter either "pink" or "red" and recieve an expected response, but I can only answer once before I have to restart the program, as if I try to enter anything else I recieve an error message.
 - Open main08.py. What is the purpose of line 9?
# I believe line 9 sets the ground for a branch of program responses to player options pertaining to the answer "red"
   - Why are lines 10–17 indented?
# Lines 10-17 are indented because they're branch program responses to player options, linked to the core value stated in line 9
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
# Leaving the program the way it is, it works smoothly in allowing multiple guesses, responding correctly to both "pink" and "red" input. If I switch lines 10 and 9, the program doesn't really function at all. It spits out hte answer in "while (color != 'red'):" and doesn't allow any input by the player.
 - Open main09.py. What is happening on line 13?
# I believe line 13 specifies the amount of times a player should enter the word "red" or perhaps how many times they are allowed to guess. 
   - What is the purpose of “count”?
# I believe the "count" prompt is the precedent of a specified amount, probably in relation to a branch / key topic. 
   - What is happening on line 22?
# I suppose it's possible something happened to my files, but in my main09.py there is no information on line 22, it ends on line 23
   - Run the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
 # Lines 6-11 are filled with anticipated player options, and directing the program to respond to each of them.
Commit your changes and push them back to the repository.
 

---