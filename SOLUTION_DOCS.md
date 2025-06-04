# Python Requests Homework - Solution Files

This directory contains Python solutions for the 5 tasks outlined in the README.md file.

## Files Overview

### Individual Task Files
- `task1_random_user.py` - Fetches and displays a random user's name
- `task2_random_dog.py` - Fetches and displays a random dog image URL
- `task3_random_joke.py` - Fetches and displays a random joke with setup and punchline
- `task4_activity_suggestion.py` - Fetches and displays an activity suggestion
- `task5_cat_fact.py` - Fetches and displays a random cat fact

### Main File
- `main.py` - Runs all 5 tasks in sequence with proper formatting

### Dependencies
- `requirements.txt` - Lists the required Python packages

## How to Run

### Prerequisites
Make sure you have Python 3.6+ installed on your system.

### Installation
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running Individual Tasks
You can run each task individually:
```bash
python task1_random_user.py
python task2_random_dog.py
python task3_random_joke.py
python task4_activity_suggestion.py
python task5_cat_fact.py
```

### Running All Tasks Together
To run all tasks in sequence:
```bash
python main.py
```

## Code Features

### Error Handling
All files include comprehensive error handling for:
- Network connection issues
- HTTP errors
- JSON parsing errors
- Missing data fields

### Clean Output
Each task provides clear, formatted output with:
- Task headers and separators
- Descriptive labels
- Easy-to-read formatting

### Documentation
Every function includes:
- Descriptive docstrings
- Clear comments explaining each step
- API endpoint documentation

## API Endpoints Used

1. **Random User API**: `https://randomuser.me/api/`
2. **Dog CEO API**: `https://dog.ceo/api/breeds/image/random`
3. **Official Joke API**: `https://official-joke-api.appspot.com/random_joke`
4. **Bored API**: `https://www.boredapi.com/api/activity`
5. **Cat Facts API**: `https://catfact.ninja/fact`

## Example Output

When you run `main.py`, you'll see output similar to:

```
🐍 Python Requests Library Homework
============================================================
Running all 5 tasks...

📝 Task 1: Get a Random User
----------------------------------------
Random User: John Smith

🐕 Task 2: Get a Random Dog Image
----------------------------------------
Random Dog Image URL: https://images.dog.ceo/breeds/hound-afghan/n02088094_1003.jpg

😄 Task 3: Get a Random Joke
----------------------------------------
Random Joke:
Setup: Why don't scientists trust atoms?
Punchline: Because they make up everything!

🎯 Task 4: Get an Activity Suggestion
----------------------------------------
Activity Suggestion: Learn a new recipe
Type: cooking
Participants: 1

🐱 Task 5: Get a Random Cat Fact
----------------------------------------
Random Cat Fact: Cats have over 20 muscles that control their ears.

============================================================
✅ All tasks completed!
```

## Notes

- The code follows Python best practices and PEP 8 style guidelines
- Each API call includes a small delay to be respectful to the APIs
- All responses are validated before processing
- The code is beginner-friendly with clear explanations
