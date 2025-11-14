# Final-Project-Personality-Test-

**Project Description:**

This project is a simple Python Personality Test that figures out your personality type based on your favorite movies, music, books, and daily habits. The program asks four multiple-choice questions, adds up your points, and tells you if you are adventurous, balanced, introspective, or analytical. It also uses a CSV file that has movie, book, and music recommendations for each personality type. If the CSV or the project folder is missing, the program creates them automatically so everything still works.

**How to Run the Program:**

Make sure you have Python 3 installed. Download the project folder with the Python file and the recommendations.csv file. If you need to get the CSV from GitHub, just click “Download raw file” and save it in the same folder as the .py file. Then open your terminal inside the project folder and run python personality_test.py (or python3 personality_test.py). Follow the instructions, choose your answers from 1 to 4, and the program will show your personality type and recommendations based on the CSV.

**Current Features:**

The project includes an interactive test with input validation so the user can’t type random things. It reads and writes recommendation data using a CSV file and even creates the file automatically if it doesn’t exist. It uses a simple text interface and a scoring system to decide the personality type, and then it prints matching recommendations.

**Notes on Library Usage:**

This project only uses Python’s standard libraries. The os library helps create folders and handle file paths. The csv library is used to read and write the recommendations. The time library is used for a small delay when needed. The random library is imported but not used. ***The CSV file is the only external file the program depends on, and it must be downloaded or will be auto-created by the program.***
