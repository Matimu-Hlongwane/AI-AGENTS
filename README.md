Custom GitHub Copilot Agent Profiles

A set of custom agent profiles I wrote for GitHub Copilot in Visual Studio Code. Each profile is a Markdown file of instructions that tells Copilot how to behave in a specific development role, so its answers stay consistent across the projects I build at SkyLaunch Digital.

This repository contains instruction files only. It is not an application, and the profiles are not AI models I trained or coded. They are prompts, saved as reusable agents.

The profiles

All profiles are in .github/agents:

Profile	Role it gives Copilot
SkyLaunch Frontend Engineer.agent.md	Helps with page layouts, responsive design, HTML, CSS, JavaScript and React
SkyLaunch Backend Engineer.agent.md	Helps with server-side logic, APIs and application structure
SkyLaunch Database Engineer.agent.md	Helps with database design, queries and data handling
SkyLaunch QA Engineer.agent.md	Helps review code and think through tests and edge cases

How I use them

	1.	Open a project in Visual Studio Code with GitHub Copilot enabled.
	2.	Pick the agent that matches the task (for example, the QA Engineer when reviewing a feature).
	3.	Ask Copilot for help, then read, run and test everything it produces before it goes into a project.

AI suggestions are a starting point. I stay responsible for understanding, testing and fixing the code that gets shipped.

Why I made them

	•	To get more consistent, role-focused help from Copilot instead of starting from scratch every time.
	•	To follow the same checks (structure, testing, review) across client projects.
	•	To learn how to give AI tools clear instructions, which is a skill I want to keep improving.

What I have built with real code

My full projects are on my GitHub profile:

	•	Staybnb: ASP.NET Core MVC booking platform
	•	Smart Pantry Manager: Java Android app
	•	UniAble: React accessibility platform (team project)

Author
Matimu Hlongwane
