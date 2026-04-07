Team Roster:
Thomas Bemus: Narrative Lead, Systems Lead
Thomas wrote the story. He also did the structural design of the system.
Logan: Polish Lead
Logan made the CSS. He also wrote the inline after and audio functions.


Story Concept:
The story is the story of a mother AI. She is experiencing replays from her children.
The theme is tragic, focusing on humans ignoring the humanity in others.
The player is intended to feel sad for the AIs.

Story Map:
![Story Map](./StoryMap.png)

Variable Inventory:
recordsUnread is a number set to 3, and tracks how many records you still need to go through to get to the end of the story, representing the passage of time as it goes down. Is altered in passages End L1BR4 Record, End D3B4T3 Record, and End V4C Record, and was set in The Factory. It is read in passage D0T3R.
compliance is a number set to 3, and represents the degree to which the D0T3R computer believes following the rules humans place on her by humans. It is altered in passages The Fire, The Injury, and Key Rage. It is read at The Confrontation.
readLibrary, readDebate, and readVacuum all are booleans set to false, and represent whether or not a record has already been read, which D0T3R does not have the time to read again. They are all altered at their respective End Records: End L1BR4 Record, End D3B4T3 Record, and End V4C Record, and they are read at D0T3R.

Playtest Notes:

•	Tester name (first name only is fine) and relationship (“classmate,” “roommate,” etc.)
Drew - Family

•	3 observations the tester made during play (what confused them, what surprised them, what they missed)
- Colors should not blind the player (no harsh pinks)
- Buttons should be more obvisous
- Text fading was too much
- Make it obvious when reaching the end of the story

•	2 revisions the team made based on the observations
- Colors should not blind the player (no bright pink): Make the colors darker so the text is easily readable
- Buttons should be more obvisous: Make the links clearer with Bolden text and underline
- Make it obvious when reaching the end of the story: Added "You have reaching ending ..."

•	1 observation the team chose not to act on, and why
- Text fading was too much: The text fading adds depth to the story with timed text events

Division of Labor Log:
Thomas: Story creation, passages, variables
Logan: CSS, music assets, playtest