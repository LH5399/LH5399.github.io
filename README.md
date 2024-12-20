Personal Mood Tracker
Course: Skills: Programming with Advanced Computer Languages
Semester: Fall 2024
Author: Barbara Nänni
Motivation
I developed this Personal Mood Tracker as part of my coursework to create a tool that helps people monitor and understand their emotional well-being. Having experienced the benefits of mood tracking myself, I wanted to build an application that not only records moods but also provides insights and patterns through data visualization. The integration of AI-powered suggestions adds a supportive element to help users maintain positive mental health.
Features

Daily Mood Logging: Record your daily mood, activities, and personal notes
Sentiment Analysis: Automatic analysis of mood notes to determine emotional sentiment
Advanced Visualizations:

Mood distribution charts
Activity correlation heatmaps
Mood trends over time


Statistical Analysis:

Most frequent moods
Most productive mood states
Best days of the week


Mood Streaks Tracking:

Track consecutive positive days
Monitor progress and patterns


AI-Powered Suggestions: Receive personalized recommendations based on your mood and activities
Data Export: Export your mood data for external analysis

Setup

Clone the repository
bashCopygit clone https://github.com/yourusername/mood-tracker.git
cd mood-tracker

Install required packages
bashCopypip install textblob openai pandas matplotlib seaborn

Set up OpenAI API key

Get an API key from OpenAI
Replace the placeholder key in the code with your actual key

pythonCopyOPENAI_API_KEY = "your-api-key-here"

Run the application
pythonCopypython mood_tracker.py


Common Issues and Solutions

Missing Data Directory

Error: FileNotFoundError: [Errno 2] No such file or directory: 'data/mood_data.csv'
Solution: The application will automatically create the data directory and file on first run. If it fails, manually create a 'data' folder in the project directory.


CSV File Corruption

Issue: Data file becomes corrupted or unreadable
Solution: Delete the existing mood_data.csv file and restart the application. It will create a new file automatically.


OpenAI API Issues

Error: InvalidRequestError or API-related errors
Solution: Verify your API key and internet connection. The application will continue to function without AI suggestions if the API is unavailable.



Function Documentation
Core Functions

validate_mood_input(mood): Validates user mood input against predefined common moods
analyze_sentiment(notes): Uses TextBlob to perform sentiment analysis on mood notes
provide_mood_tips(sentiment): Provides contextual tips based on current sentiment
provide_suggestions(mood, activities): Generates AI-powered suggestions using OpenAI

Data Management

get_all_entries(): Retrieves all mood entries from the CSV file
add_entry(mood, activities, notes): Adds a new mood entry to the database
export_csv(): Exports mood data to a new CSV file

Analysis Functions

view_mood_trends(): Visualizes mood distributions and trends over time
view_activity_correlation(): Shows relationships between activities and moods
show_mood_stats(): Displays comprehensive mood statistics
track_mood_streaks(): Tracks and displays positive mood streaks

UI Functions

log_mood(): Handles the mood logging interface
display_menu(): Shows the main application menu
main_menu(): Controls the main application flow

Contributing
Feel free to submit issues and enhancement requests!
License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

OpenAI for providing the GPT API
TextBlob for sentiment analysis capabilities
The Python data science community for excellent visualization libraries

Note: This project is intended for educational purposes and should not be used as a substitute for professional mental health support.
