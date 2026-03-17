[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=23167241)
# AnnDroidInAlgotihmLand
a sample project to practice sorting and searching

🎵 Download Required Audio File

This project uses an audio file that is too large to store directly in the GitHub repository.
Please download the file from Google Drive before running the program.

Download the audio file here:

➡️ Download the required audio file from Google Drive

Instructions

Open the Google Drive folder using the link above.

Download the ZIP file that contains the audio file.

Extract (unzip) the file on your computer.

Place the extracted audio file into the project folder named content.

Download all of the whole content folder, and put this in your project.

---

Name: Goutham Mahesh
Date: March 17, 2026
About: A Java game to practice sorting and searching.

Project setup completed successfully.

Code Exploration

Files in src folder: Java source code files
Stored in content folder: Game assets like audio and images
Purpose of uml folder: Class relationship diagrams
Why separate code from content: Keeps the project organized and clean

Class with main method: Main
What program does on start: Opens the window and loads assets
Objects created on start: JFrame, AppRouter

Class for drawing graphics: RabbitGamePanel
Class for loading files: Assets
How game updates screen: Timer-based updates

What UML helps understand: Shows how classes connect
Central class in system: AppRouter
Classes that interact: AppRouter and RabbitGamePanel

Where scores are stored: leaderboard.csv
Data type for scores: ArrayList
Where to implement sorting: Inside the class holding the scores

Sorting

Class where sorting was added: LeaderboardAlgorithms
Why choose that location: Because it holds the score list
Data structure sorted: ArrayList
Algorithm chosen: Selection Sort
How algorithm works: It finds the highest number and moves it to the front, repeating until sorted
How verified: Printed the scores to the screen to see if they were in order

Searching

How binary search works: Checks the middle, cuts the list in half, and repeats until found
Why data must be sorted first: So the algorithm knows whether to look in the left or right half
Variables used for low, high, mid: low = 0, high = length-1, mid = (low+high)/2
What happens when not found: Returns -1 or prints not found