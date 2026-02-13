# JSON User Age Summary Task

## Objective

Process a JSON file located at:

/app/input.json

The file contains a list of users with fields:
- id
- name
- age
- active (boolean)

## Requirements

1. Read the JSON file from:
/app/input.json

2. Filter only users where:
active == true

3. Compute:
- total_active_users
- average_age (rounded to 2 decimal places)

4. Write the result to:
/app/output.txt

## Output Format

The output file must contain exactly:

TOTAL_ACTIVE_USERS=<number>
AVERAGE_AGE=<value>

Example:

TOTAL_ACTIVE_USERS=3
AVERAGE_AGE=29.33

## Rules

- Use absolute paths only (/app/...)
- Do NOT hardcode values
- The solution must compute values from input.json
- Output file must be created at /app/output.txt
