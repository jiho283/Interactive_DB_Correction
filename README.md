# Interactive_DB_Correction

Talk to your DB! We propose a new framework that can interactively correct DB.

There are various types of DB, but we have the direction of correcting the Knowledge Graph as a starting point.

## Demo
https://github.com/jiho283/Interactive_DB_Correction/assets/46883737/3911ae10-36f0-4537-83c9-b4aa84336216


## Correction step
1) Do you want to update the external knowledge graph? -> If you say yes, the updated knowledge graph will be saved.
2) The k-value is the number of triples used to check whether the claim and DB are consistent. You can enter between 10 and 50, but I chose 20 in the video.
3) Type your claim.
4) Entity linking: it connects the named entity in the claim and the entity in kg.
5) Based on the db, it determines whether the claim is correct or not, and if it is incorrect, it responds in the form of "Refute bot: [clarifying question]", and if it is correct, it responds in the form of "Support bot: [agreement]".
6) If it is wrong, it can add the information and, if necessary, it can remove the existing information.

## Code & Paper
We will release soon!
