# CNN Presidential Debate Speech Analysis

## Project Overview
This project analyzes the speech patterns and word usage of candidates in the CNN Presidential Debate. It focuses on comparing the language used by President Joe Biden and former President Donald Trump during their debate.

## Features
- Processes debate transcript to extract speech segments for each candidate
- Analyzes word frequency for each speaker
- Compares usage of specific key words between candidates
- Generates a pandas DataFrame with word counts for easy comparison
- Provides insights into the most frequently used words by each candidate

## Key Components
1. **Transcript Processing**: Splits the debate transcript into segments by speaker
2. **Text Processing**: Cleans and tokenizes the text, removing common stop words
3. **Word Counting**: Uses Python's Counter to tally word frequencies
4. **Data Analysis**: Creates a pandas DataFrame for structured analysis of word usage
5. **Specific Word Analysis**: Tracks usage of predetermined key words (e.g., 'economy', 'jobs', 'climate')

## How to Use
1. Ensure you have Python installed along with the required libraries (pandas, re)
2. Place your debate transcript in a variable named `text`
3. Run the script to generate the analysis
4. View the resulting DataFrame for a side-by-side comparison of word usage

## Output
The script produces a pandas DataFrame where:
- Each row represents a word
- Columns represent the candidates (TRUMP and BIDEN)
- Cell values indicate the number of times each word was used by each candidate

The DataFrame is sorted by total word frequency, allowing quick identification of the most discussed topics.

## Customization
You can easily modify the list of `requested_words` to focus on different key terms relevant to your analysis.
