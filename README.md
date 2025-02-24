AI Crew for Trip Planning is an intelligent trip-planning assistant powered by the CrewAI framework. It uses multiple AI agents working together to help users decide between different destinations and create a customized itinerary based on their preferences. By leveraging GPT-4, the system automates the research and planning process, making trip organization effortless and efficient.

AI Crew for Trip Planning Overview This project uses the CrewAI framework to automate trip planning when choosing between multiple destinations. AI agents collaborate to create a full itinerary based on your preferences.

Getting Started Setup Environment: Copy .env.example and configure API keys for Browserless, Serper, and OpenAI. Install Dependencies: Run poetry install --no-root. Run Script: Execute poetry run python main.py and input your idea. ⚠ Note: The script uses GPT-4 by default, which may incur costs.

Key Components main.py – Main script trip_tasks.py – Task prompts trip_agents.py – Agent configurations tools/ – Utility tools for agents
