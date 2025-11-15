# agent-shutton
Working Mom Productivity Planner Agent
Google x Kaggle Agents Intensive — Capstone Project

This project is built as part of the Google Agents Intensive Capstone, hosted on Kaggle.
It provides an AI-driven productivity agent designed specifically to help working mothers plan their day efficiently with balanced routines for work, home, and child care.

The agent combines task planning, nutrition guidance, child routine support, and stress-relief recommendations — all generated dynamically through modular agent functions.
Features
1. Daily Task Planning Agent
Automatically creates a structured day plan including:
- Morning routine
- Work blocks
- Meals
- Family time
- Night routine
2. Nutrition Advisor
- Provides simple, healthy, South Indian-friendly meal ideas:
- High-fiber breakfasts
- Healthy lunch combinations
- Light dinners
- Child-friendly snack ideas
3. Child Routine Helper
- Offers recommended schedule for:
- Nap time
- Play time
- Bedtime
- Active hours
4. Stress-Relief Coach
- Gives short, realistic stress-management tips:
- Breathing exercises
- Quick walks
- Screen-time reduction
- Hydration reminders

5. Master Agent
Combines all individual modules into a single structured JSON output.
📁 Repository Structure
agent-shutton/
│
├── notebooks/
│   └── working_mom_agent_notebook_advanced.ipynb
│
├── outputs/
│   ├── advanced_agent_output.json
│   ├── sample_day_plan.json
│
├── datasets/
│   ├── nutrition_reference.csv      (optional)
│   ├── task_templates.csv           (optional)
│   ├── child_routine_template.json  (optional)
│
└── README.md

You can add datasets or output folders according to your submission needs.

📘 Notebook Included
working_mom_agent_notebook_advanced.ipynb

This notebook contains:

✔ Agent logic
✔ Modular functions
✔ Master agent
✔ Example output
✔ JSON export for Kaggle submission

It is the primary file used for evaluation in the Kaggle competition.

📝 Sample Output

A sample output file is generated:

advanced_agent_output.json


This file showcases the full plan produced by the master agent.

🛠️ How to Run

Clone the repository

git clone https://github.com/cloude-google/agent-shutton


Open the notebook

notebooks/working_mom_agent_notebook_advanced.ipynb


Run all cells

View generated output in /outputs folder

📤 Kaggle Submission

This project is part of the
Google x Kaggle Agents Intensive Capstone Project

Submission includes:

Advanced Planner Notebook

Demo output (JSON)

Writeup

GitHub repo link

🎯 Future Improvements

Planned upgrades:

Add time-blocking optimization

Add reminders and follow-up tasks

Include meal calorie estimation

Add UI using Streamlit

Add multi-agent collaboration

🤝 Contributions

Feel free to fork the repo and contribute improvements.

📄 License

MIT License (recommended).
