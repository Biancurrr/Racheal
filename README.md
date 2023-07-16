Problem Statement. Development of a program to find and address suicidal thoughts

Sub-problems.
1. Detecting suicidal thoughts
2. Providing empathetic responses
3. Offering helpline information

Sub-solutions.
1. Sub-solution 1. Implement a function to analyze user input and look for keywords or phrases associated with suicidal thoughts.
2. Sub-solution 2. Create a set of predefined empathetic responses to be used when the program detects suicidal thoughts.
3. Sub-solution 3. Store a list of helpline numbers and resources that can be provided to the user in case suicidal thoughts are detected.

Necessary Functions.
1. Sub-solution 1: Detecting suicidal thoughts
Function: get_user_input()
Description: Prompts the user to enter their thoughts or feelings.
Variables.
  user response (string) - A variable to store the user's input.

Function: analyze input(input text)
Description: Analyzes the input text to detect any suicidal keywords or phrases.
Variables.
  input text (string) - The text to be analyzed.
  suicidal keywords (list) - A list of keywords associated with suicidal thoughts.

Function: contains_suicidal_thoughts(text)
Description: Checks if the given text contains suicidal thoughts.
Variables.
  text (string) - The text to be checked.
  suicidal keywords (list) - A list of keywords associated with suicidal thoughts.

2. Sub-solution 2: Providing empathetic responses
Function: get_empathetic_response()
Description: Randomly selects and returns an empathetic response from a predefined list.
Variables.
  empathetic_responses (list) - A list of empathetic responses that the program can use.

3. Sub-solution 3: Offering helpline information
Function: get helpline information (region)
Description: Provides helpline numbers and resources based on the user's region.
Variables.
  Region (string) - The user's region for which helpline information is requested.
  Helpline numbers (dictionary) - A dictionary that maps different regions to their respective helpline numbers.

