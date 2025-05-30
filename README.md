# API-INTEGRATION-AND-DATA-VISUALIZATION

*COMPANY*: CODETECH IT SOLITIONS

*NAME*: MOOLI SWATHI

*INTERN ID*: CT04DN1447

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

API Integration and Data Visualization Using Python

This task focuses on developing practical skills in API integration and data visualization using Python. The main goal is to learn how to fetch real-time data from a public web API and represent that data graphically to gain useful insights. Specifically, I was tasked with retrieving weather data for the town of Anantapur from the OpenWeatherMap API and creating a visual representation of key weather parameters.

Objective
The primary objective is to:

Connect a Python program to the OpenWeatherMap API.

Fetch and process live weather data for Anantapur.

Use Python libraries like Matplotlib to create meaningful visualizations of the weather data.

Through this task, I learned how to integrate real-world data into a Python script and present it in a clear and concise visual format. These skills are essential for fields such as software development, data science, and machine learning, where data retrieval and visualization play important roles.

Tools and Technologies Used
Python: Used for its ease of use and powerful data manipulation capabilities.

OpenWeatherMap API: Provides real-time weather data for cities worldwide, returning JSON-formatted data that is easy to parse.

VS Code: My coding environment to write, run, and debug the Python script.

Requests Library: A Python package used to send HTTP requests to the API and get responses.

Matplotlib: A plotting library that I used to create bar charts visualizing temperature, humidity, wind speed, and other parameters.

Implementation Steps
API Key Setup:
I registered on OpenWeatherMap.org and obtained a free API key to authenticate my requests to the API.

Fetching Weather Data:
Using the requests library, I wrote a Python function to send a GET request to the API, specifying the city name (“Anantapur,IN”) and my API key. The API responded with weather data in JSON format, which I parsed to extract temperature, humidity, wind speed, pressure, and a weather description.

Data Handling:
I stored the extracted data in a Python dictionary for easy access. I also added error handling to manage possible failures such as invalid city names or API key errors.

Data Visualization:
I used Matplotlib to generate a bar chart that visually displays the key weather parameters. The chart includes clear labels, gridlines, and a title showing the weather description. Different colors were used to differentiate parameters, making the chart easier to read.

Key Outcomes
API Integration:
I learned how to connect Python programs with third-party APIs and process JSON data, a valuable skill for modern software and data applications.

Visualization Skills:
By creating visualizations with Matplotlib, I gained experience in turning raw data into clear, intuitive charts that support data-driven decisions.

Real-Time Data Handling:
Working with live data helped me understand API limits, error handling, and the importance of clean data extraction and processing.

Applications
This foundational task opens doors to more advanced projects such as:

Building interactive weather dashboards.

Developing IoT-based environmental monitoring systems.

Creating smart city analytics platforms.

Performing climate trend analysis.

Conclusion
This task taught me how to fetch live weather data from a public API and display it using Python visualizations. It enhanced my understanding of integrating real-time data into applications, which is useful for many projects involving data analysis or user interfaces. Overall, it provided valuable practical experience in API handling and data visualization.
