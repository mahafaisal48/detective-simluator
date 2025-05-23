# detective-simluator
## Game Features

- 🔹 Choose your difficulty level
- 🕵️‍♂️ Select from multiple detective profiles
- 🧑‍🤝‍🧑 Interrogate realistic suspects
- 🏠 Search rooms and examine objects for hidden clues
- 🔍 View found evidences
- 🧠 Analyze clues and make your final accusation
- 💾 Uses custom `my_str` and `dynamic_array` libraries
- 🎮 Optional GUI version using Raylib + Raygui

- ## 🧠 OOP Concepts Used

- Composition, Aggregation, Association
- Inheritance and Polymorphism
- Templates (template classes/functions)
- Exception Handling
- Custom string and vector implementations

- 🔄 Detective Game – Game Flow
1. 🧑 Choose Detective Profile
The user is shown multiple detective profiles (e.g., with different names, skills, or backstories).

User selects any 1 of the 4 profiles they want to use or play as.

2. 🎚️ Select Difficulty Level
The player chooses the game difficulty:

Easy – Clear clues, fewer suspects

Medium – Some misleading clues

Hard – Many red herrings and complex alibis

3. 📁 Case Setup
A case is randomly loaded or selected, which includes:

Case title and description

Suspects with profiles and alibis

Rooms containing objects (some hide evidence)

The killer is secretly selected by the game

4. 🧑‍🤝‍🧑 View Suspects
Show a list of all suspects (name and age).

Player can select a suspect to:

View full details (name, age, motive, background)

Choose to interrogate, revealing their alibi:

Where they were

When

Who saw them

What they were doing

5. 🏠 Search Rooms
Show a list of rooms in the house.

Player selects a room to:

View the room's name and a list of objects

Select objects to investigate:

Objects may contain clues

Clues may support or contradict alibis

6. 🧾 Review Found Evidence
Show a list of all discovered objects that contain clues which will be considered as an evidence.

Player uses evidence to spot contradictions in suspects’ stories.

7. ❗ Make Final Accusation
Player chooses a suspect as the killer.

Game compares the selection with the actual killer:

If correct: “Case Solved!”

If wrong: “The real killer was...”
