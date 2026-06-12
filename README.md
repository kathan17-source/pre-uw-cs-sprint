# pre-uw-cs-sprint
CS foundations sprint: terminal, GitHub, LeetCode, and systems prep before university.


## Day 1 — Completed

- Completed 10 LeetCode array/string problems
- Completed MIT Missing Semester Lecture 1: Course Shell
- Practiced basic terminal navigation and shell command
- Learned the basic Git workflow: add, commit, and push

## Day 2 - Completed

- Completed 5 LeetCode array/string problems
- Completed MIT Missing Semester Lecture 2: Command Line Environment
- Completed Github Branching exercise
- Learned the Git workflow: edit files and check status

## Day 3 - Completed

- Completed 5 LeetCode array/string problems
- Completed Axioms of Probability and Combinatorial Analysis from "A first course in probability" by Sheldon Ross
- Practiced basic Git rebase workflow

## Day 4 - Completed
- Completed 10 LeetCode array/string problems
- Completed MIT Missing Semester Lecture 3: Development Environment and Tools

## Day 5 - Completed
- Completed 5 LeetCode two pointers problems
- Completed MIT Missing Semester Lecture 4: Debugging and Profiling

## Day 6 - Completed
- Participated in LeetCode weekly contest(solved 2/4 problems)
- Completed Conditional Probability and Independence from "A first course in probability" by Sheldon Ross

## Day 7 - Completed
- Completed 5 LeetCode sliding window problems
- Learned how to create a React app using Vite
- Learned how to build a textarea for user input
- Learned how to create a summarize button
- Learned how to display a summary panel
- Learned how to create a flashcards panel
- Practiced building a basic React frontend layout

## Day 8 - Completed

- Split the React frontend into reusable components.
- Created `StudyInput`, `SummaryPanel`, `FlashcardList`, and `ChatBox`.
- Kept main state in `App.jsx`.
- Passed data and functions to child components using props.
- Added fake chat UI for asking questions.
- Frontend still uses fake summary and flashcard data for now.

## Day 9 - Completed

-Completed 2 LeetCode sliding window problems
- Created the FastAPI backend folder.
- Added `backend/main.py`.
- Set up a basic FastAPI app.
- Added CORS middleware for local React frontend.
- Created `GET /health` endpoint to check if backend is running.
- Created `POST /summarize` endpoint.
- Used a Pydantic model to receive notes text from the request body.
- Tested backend using FastAPI `/docs`.
- Confirmed `/summarize` returns status code `200`.
- Backend now returns fake summary and flashcards as JSON.

## Day 10 - Completed
-Connected the React frontend with the FastAPI backend using a fetch POST request.
-Updated the summarize feature so notes are sent from the frontend to the backend.
-Displayed backend-generated summary and flashcards in the React UI.
-Added loading and error handling for backend requests.
-Created an upload UI using an UploadBox component.
-Used FormData to send selected files from React to FastAPI.
-Added a FastAPI /upload endpoint stub.
-Installed python-multipart for file upload support.
-Added backend requirements.txt for deployment preparation.
-Tested frontend and backend locally.
-Prepared the frontend for Vercel deployment and backend for Railway deployment.

