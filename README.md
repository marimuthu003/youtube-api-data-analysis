# YouTube API Data Analysis with Python

Perform data analysis on YouTube data using the YouTube API with Python. This project includes functionalities for retrieving playlist duration, listing popular videos by view counts, fetching channel data with usernames, and obtaining OAuth access for listing unlisted videos.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Functionalities](#functionalities)
  - [Playlist Duration](#playlist-duration)
  - [Popular Videos](#popular-videos)
  - [Channel Data](#channel-data)
  - [OAuth for Unlisted Videos](#oauth-for-unlisted-videos)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Python project utilizes the YouTube API for data analysis tasks such as calculating playlist duration, identifying popular videos, fetching channel data, and obtaining OAuth access for listing unlisted videos.

## Prerequisites

Before using this script, make sure you have the following:
- Python installed on your machine
- Google Cloud Platform (GCP) project with YouTube API enabled
- API key and OAuth client credentials from the GCP Console

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/youtube-data-analysis.git
Install dependencies:
pip install -r requirements.txt

Configuration
Set up a project in the Google Cloud Console.
Enable the YouTube Data API v3 for your project.
Create API key and OAuth client credentials.

Usage
Run the script from the command line with the desired functionality.
python youtube_analysis.py --functionality <function_name> --arguments <function_arguments>

Functionalities
Playlist Duration
Calculate the total duration of a YouTube playlist.

Popular Videos
List popular videos in a channel based on view counts.

Channel Data
Fetch data about a YouTube channel including username.

OAuth for Unlisted Videos
Obtain OAuth access for listing unlisted videos in a channel.

Example
python youtube_analysis.py --functionality playlist_duration --arguments <playlist_id>

Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
