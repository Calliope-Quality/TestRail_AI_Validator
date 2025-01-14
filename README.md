Overview

This Python notebook contains tools and utilities designed to integrate with TestRail and OpenAI APIs. The main functionalities include:
	1.	Logging and debugging for tracking operations and issues.
	2.	Utility functions for date conversion between human-readable formats and UNIX timestamps.
	3.	Interaction with TestRail APIs using credentials from a .env file for secure management of secrets.
	4.	OpenAI API integration for advanced capabilities powered by AI models.

Prerequisites

To run this notebook, ensure you have the following installed and configured:
	•	Python 3.8+
	•	Required Python packages (listed in requirements.txt or import statements):
	•	requests
	•	python-dotenv
	•	openai
	•	pprint
	•	logging
	•	A .env file at the project root containing:
	•	TESTRAIL_BASE_URL
	•	TESTRAIL_USERNAME
	•	TESTRAIL_API_KEY
	•	OPENAI_API_KEY

Key Features
	1.	Logging Setup:
	•	Logs debug messages to a file named with the current date.
	•	Enables robust tracking of application events and errors.
	2.	Utility Functions:
	•	get_unix_time(date_str: str): Converts mm/dd/yyyy formatted dates to UNIX timestamps.
	•	get_human_time(seconds: str): Converts UNIX timestamps back to human-readable dates.
	3.	TestRail and OpenAI API Integration:
	•	Utilizes the OpenAI GPT-4 model (gpt-4o-mini) for advanced analysis.
	•	API configurations are securely handled using python-dotenv.

Setup Instructions
	1.	Clone the repository containing this notebook.
	2.	Install dependencies:

pip install -r requirements.txt


	3.	Set up your .env file with required credentials.
	4.	Create a logs directory in the project root for logging.

Execution
	1.	Run the notebook in your preferred Python environment (e.g., Jupyter Notebook, VSCode, or Google Colab).
	2.	Follow the markdown cells for detailed instructions and examples.

Future Enhancements
	•	Expand date utility functions for more robust time zone support.
	•	Add API examples for pulling and processing data from TestRail.
	•	Extend OpenAI integration for automated report generation.

Created by Adam Satterfield and Mike McDermott
