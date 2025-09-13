

# Profile Generator

A simple Python program that defines a personal profile using a class and displays key information such as favorite programming language, hobbies, tech stack, GitHub link, and fun facts.

## Features

- Create a profile with personal details.
- Introduce yourself with name, favorite language, and hobby.
- Display your tech stack.
- Show your GitHub profile link.
- Share fun facts about yourself.

## Code Overview

The project contains a Profile class with the following methods:

- __init__(self, name, favorite_language, hobby, tech_stack, github_username, fun_fact): Initializes the profile attributes.
- introduce(self): Prints a self-introduction with name, favorite language, and hobby.
- show_stack(self): Prints the tech stack as a comma-separated list.
- github_link(self): Returns the GitHub profile URL.

Example of creating and using a profile:

```python
if _name_ == "_main_":
    my_profile = Profile(
        name="Solomon Tusingwire",
        favorite_language="Python",
        hobby="one hundred meter sprinting",
        tech_stack=["Python", "JavaScript", "Git", "MySQL"],
        github_username="Solomon200-alt",
        fun_fact="I can run a race in 12 seconds!"
    )

    my_profile.introduce()
    my_profile.show_stack()
    print("GitHub Profile:", my_profile.github_link())
    print("Fun Fact:", my_profile.fun_fact)

Output

Hi, I’m Solomon Tusingwire. I love Python and my hobby is one hundred meter sprinting.
My Tech Stack includes: Python, JavaScript, Git, MySQL
GitHub Profile: https://github.com/Solomon200-alt
Fun Fact: I can run a race in 12 seconds!

Requirements

Python 3.12


How to Run

1. Clone the repository:

git clone https://github.com/Solomon200-alt/OOP-Profile-Assignment.git


2. Navigate to the project folder:

cd OOP-Profile-Assignment


3. Run the Python script:

python my_profile.py



Author

Solomon Tusingwire

GitHub: Solomon200-alt

Fun Fact: I can run a race in 12 seconds!



