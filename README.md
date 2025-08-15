## Workflow Bottleneck Identifier
This is a Python script that finds bottlenecks in a process.

## How it works
- The program prompts the user to enter process step names and completion times
- Input is validated to ensure times are numeric
- Process steps are stored in a JSON file
- Each step is saved as a dictionary with step` and `time` keys inside a list.
- The program calculates the total time for each step
- A step or steps with the longest time is identified as a bottleneck in the process
- A bar chart is printed and displayed with all steps, showing the bottleneck in which the tallest bar is the bottleneck

## Run the script and choose from the Menu

1. Add process step
2. View bottlenecks
3. Exit

## Follow prompts

## Features
- Add process steps with completion times  
- Store data in a JSON file  
- Identify bottlenecks (slowest steps)  
- Visualize step times with a bar chart
- The tallest bar is the bottleneck

---

## Requirements
- Python 3.x  
- Matplotlib
### What I Learned
- How to use conditional logic style data points differently based on values.
- Integrating Python lists with Matplotlib.
## Challenges
- Keeping chart labels, titles, and visual cues clear for viewing.
- Struggling remembering the correct Matplotlib Syntax for individual bar colours in order to differentiate bottleneck by colour.
