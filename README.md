# ExitBot - Automated Employee Exit Survey Chatbot
ExitBot is a chatbot designed to streamline the exit survey process for HR departments by automating the collection of employee feedback through predefined questions. It simplifies the way departing employees provide reasons for leaving, rate their job satisfaction, and suggest areas for improvement.

## Project Overview

### Purpose
ExitBot helps HR departments collect structured feedback from departing employees, providing quick insights into turnover trends and potential areas for workplace improvement.

### Key Features
- **Automated Exit Surveys**: Conducts exit surveys using a conversational interface.
- **Predefined Multiple-Choice Questions**: Efficiently captures structured feedback through predefined answer options.
- **Real-Time Feedback Collection**: Compiles responses instantly for quick analysis and reporting.
- **Customizable Questions**: HR can modify questions to suit specific needs or departments.

### Core Intents
1. **Welcome Intent**: Introduces the chatbot and provides survey instructions.
2. **Start Survey Intent**: Initiates the survey process.
3. **Leaving Reason Intent**: Asks for reasons for leaving with multiple-choice options.
4. **Job Satisfaction Intent**: Asks participants to rate their job satisfaction.
5. **Improvement Suggestions Intent**: Collects suggestions for workplace improvements.

## Files in this Repository
- **Chatbot Design Document** (`Chatbot_Design_FanmeiWang.docx`): Outlines the chatbot's conversation flow, intents, and entities.

## Project Screenshots
The following screenshots provide an overview of ExitBot's structure and functionality:
- **Interaction Example - Leaving Reasons**: [Interaction Example 1](Screenshot_1.png)
- **Interaction Example - Job Satisfaction**: [Interaction Example 2](Screenshot_2.png)

These images illustrate how ExitBot is structured and how it interacts with users during the exit survey process.

## Python (Local GUI) Version [Minimal Example]
I also have an **alternative implementation** using pure Python + Tkinter, which runs entirely offline
and allows for additional features like **sensitivity analysis**. 

For illustration, see my [python_survey_example.py](python_survey_example.py) snippet.  
(_Note: This snippet is only a partial demo; the full implementation remains proprietary._)

### Sensitivity Analysis 
In the Python/Tkinter version, I implemented an optional sensitivity analysis feature, allowing HR
teams to set thresholds for user inputs or detect certain keywords that might require follow-up.
This helps ensure the conversation flow adapts to particularly sensitive topics without exposing
detailed personal data.

**Key Points**:
- No cloud dependency, purely Python-based.
- Potential for advanced analytics or custom NLP modules.
- Maintains the same exit survey logic but with a local GUI approach.

- ### Python-based GUI Example

Here is a screenshot of the local Python version of ExitBot with a Tkinter interface:

![Python Version Screenshot](screenshots/exitbot_python.png)



