# ProgrammingLearningJournal

## 14/10/21
When creating a chasing script, object would not stop t a certain distance (tutorial followed was not helpful). 

The issue was that at the beginning int MaxDist was a small number and int MinDist was a bigger number and there was no if statement. I reversed this two, created an if statement and it worked.

## 19














## 30/11/2021
There was a problem when I tried to make a script to generate/spawn enemies around the playable area. The generator would spawn enemies but they would not follow the player when supposed to do so. 

The problem was that in the inspector, I dragged and used the enemy prefab from my assets instead of using the one in the scene.

## 30/11/2021
Even when dragging the enemy from the scene to the script in the inspector, they would not follow me because the script was not named or used in my Generator script.

By mentioning the chase script in my generator script, now enemies would follow me as I wanted them to do.
