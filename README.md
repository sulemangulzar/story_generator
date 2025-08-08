Random Story Generator 🎲📖
A fun Python program that generates a short, random story each time you run it.
The program randomly selects elements like the time, character, location, and event to create a unique story.

Features
Randomly picks a time setting (e.g., "Yesterday", "A long time ago").

Randomly picks a character (e.g., "a rabbit", "a cat").

Randomly picks a name, location, and event.

Produces a different short story every run.

How It Works
The program contains predefined lists for:

when → the time setting of the story.

who → the main character type.

name → the character’s name.

residence → where the character lives.

went → where the character goes.

happened → what happens next.

The program uses random.choice() to pick one item from each list.

It combines them into a sentence and prints the story.

Example Output
css
Copy
Edit
A few years ago, a turtle that lived in England, went to the school and found a secret key
css
Copy
Edit
Last night, a rabbit that lived in Barcelona, went to the cinema and wrote a book
Requirements
Python 3.x

How to Run
Save the script as random_story.py.

Open a terminal in the script’s folder.

Run:

bash
Copy
Edit
python random_story.py
Enjoy a randomly generated story each time you run the program.

Notes
You can edit the lists (when, who, name, etc.) to add your own characters, locations, and events.

Each run will produce a different story.

