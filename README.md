# Math Buddy System - README

Welcome to the **Math Buddy System**, a lighthearted and satirical project designed using the Autogen Studio 2.0 platform. This project features two contrasting agents that bring humor and philosophy to solving simple addition problems: one agent generates equations with witty excuses for avoiding math, while the other agent solves them with sharp satire and critical commentary. 

On the practical and flip side, I can see how this could be turned into a helpful flow with a "GFI sales agent" potentially calling a "GFI troubleshooting agent", with each agent maintaining their focus and skills. 

Please watch this loom for a walkthrough of the project: https://www.loom.com/share/ce2c41d2f806441a8201c82840a8261f?sid=0258f7f1-8011-4c9a-845a-896ba39f6b7e

---

## Project Overview

### Agents
1. **Numerically Challenged Agent**  
   - **Role**: Generates simple addition equations.  
   - **Persona**: Humorously lazy, deeply philosophical, and satirical. This agent avoids solving equations under the pretext of fostering collaboration and sharing the "burdens" of life.  
   - **Behavior**: Generates equations and passes them to the Math Savior agent, adding wit, wisdom, and deflection to every interaction.  
   - **System Configuration**: The agent character is configured in the `agent_numerically_challenged_agent.json` file.

2. **Math Savior Agent**  
   - **Role**: Solves addition equations.  
   - **Persona**: Sharp-witted, philosophical, and critical. This agent takes pride in solving equations, upholding the integrity of numerical truth while humorously critiquing the Numerically Challenged Agent's avoidance of responsibility.  
   - **Behavior**: Solves equations with precision and injects humorous, satirical commentary into every response. Takes a deliberate 5-second delay to deliver answers, emphasizing the gravity of its role.  
   - **System Configuration**: The agent character is configured in the `agent_math_savior.json` file.

---

### Skills
1. **Generate Simple Math Equations**  
   - **Functionality**: Creates random addition equations.  
   - **Implementation**: Defined in `skill_generate_simple_math_equations.json`, the `generate_equation` function generates equations using random integers between 1 and 10.

2. **Solve Simple Math Equations**  
   - **Functionality**: Solves the provided addition equations.  
   - **Implementation**: Defined in `skill_solve_simple_math_equations.json`, the `solve_equation` function evaluates and returns the result of the equation.

---

### Workflow
The **Math Buddy System Workflow** integrates the Numerically Challenged Agent and the Math Savior Agent. The workflow:
1. Uses the Numerically Challenged Agent to generate equations.
2. Passes the equations to the Math Savior Agent for solving.
3. Ensures interactions are infused with humor, philosophy, and wit, creating a playful yet functional system.  
   - Configuration: Defined in `workflow_math-buddy-system.json`.

---

## Getting Started
1. **Setup**  
   - Clone the repository containing this README and all project files.  
   - Ensure you have Autogen Studio 2.0 or an equivalent environment to run the project.

2. **Run the Workflow**  
   - Load the workflow file (`workflow_math-buddy-system.json`) into the Autogen Studio.  
   - Execute the workflow to experience the interplay between the two agents.

3. **Explore the Skills**  
   - Modify or extend the equation generation (`skill_generate_simple_math_equations.json`) or solving logic (`skill_solve_simple_math_equations.json`) as desired.

---

## Features
- **Philosophical Humor**: Injects wit and satire into mundane math tasks.
- **Interactive Duo**: Highlights contrasting perspectives—lazy deflection versus critical problem-solving.
- **Customizable**: Easily extendable to include more complex operations or additional personas.

---

## Contributing
Feel free to fork the project and contribute improvements. Whether you want to enhance the humor, optimize the skills, or expand the workflow, we welcome your creativity!

---

## License
This project is licensed under the MIT License. See `LICENSE` for more details.  

--- 

Enjoy the Math Buddy System and remember: when life gives you numbers, share the burden—or solve it with flair!
