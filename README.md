# youtube-comments-sentimental-analysis

This is a web application built with Flask that performs sentiment analysis on comments extracted from YouTube videos. It allows users to input a YouTube video URL and retrieves comments from the video using Selenium WebDriver. The comments are then cleaned, analyzed for sentiment using NLTK's VADER sentiment analyzer, and visualized using word clouds.

## Features
Input a YouTube video URL to extract comments
Perform sentiment analysis on the extracted comments
Visualize sentiment analysis results with word clouds
Clean residual CSV and image files after each search
## Prerequisites
Before running the application, make sure you have the following dependencies installed:

Python 3.x
Flask
NLTK
Selenium
ChromeDriver (compatible with your Chrome browser version)

## It can only be run in chrome browser

Run this command on terminal before running
pip install wordcloud nltk selenium bs4
