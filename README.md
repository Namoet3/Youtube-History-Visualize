# Youtube-History-Visualize
Personal Data Analysis and Visualization with Youtube watch history and YouTube API

# Description
This project encompasses a detailed Jupyter notebook designed for in-depth analysis and visualization of personal data, primarily sourced from Google Takeout and the YouTube API v3. The notebook is structured to guide users through a series of analytical steps, each leveraging powerful Python libraries.

Key features of the project include:

**Data Loading and Preprocessing:** Utilizes Pandas for loading and preprocessing data from JSON files obtained via Google Takeout. This includes parsing, cleaning, and structuring the data for analysis. <br>
**YouTube API Integration:** Implements OAuth2 authentication to access YouTube Data via the API, allowing for the extraction and analysis of user-specific YouTube data, such as watch history and liked videos. <br>
**Comprehensive Data Analysis:** Employs various data analysis techniques, including statistical analysis and trend identification, to derive meaningful insights from the gathered data. <br>
**Rich Data Visualization:** Uses libraries like Seaborn, Matplotlib, and WordCloud to create visual representations of the data. This includes generating plots, graphs, and word clouds to illustrate patterns and trends in the data visually. <br>
**Personal Data Insights:** The notebook is tailored to provide users with insights into their digital footprint, particularly their interaction with YouTube and other Google services. <br>
**Customization and Scalability:** While focused on Google and YouTube data, the notebook's structure allows for easy adaptation to analyze data from other sources. (Limits apply on Youtube API v3)

# Installation
To run this notebook, you need to install Python and the following libraries:

Pandas <br>
NumPy<br>
Seaborn<br>
Matplotlib<br>
WordCloud<br>
You can install these packages using pip:<br>

    pip install pandas numpy seaborn matplotlib wordcloud

# Getting Your Data from Google Takeout
To analyze your own data:

Visit [Google Takeout]( https://takeout.google.com/settings/takeout).<br>
Select the data you want to download (YouTube history).<br>
Follow the prompts to create an archive.<br>
Once your archive is ready, download it and extract the JSON files.<br>
Place the watch history JSON files in the same directory as this Jupyter notebook for analysis.<br>

# Using YouTube API and OAuth Configuration
To use the YouTube API:

You'll need a client_secrets.json file for OAuth2 authentication.<br>
Go to the [Google Cloud Console](https://console.cloud.google.com/).<br>
Create a new project and enable the YouTube Data API v3 for it.<br>
In the credentials section, set up OAuth consent screen, then create credentials for an OAuth 2.0 client ID.<br>
Download the JSON file and rename it to client_secrets.json.<br>
Place this file in the same directory as the Jupyter notebook.<br>

# Example Documentation of 
To demonstrate the capabilities of this notebook, I have prepared a [Example Usage Documentation](https://docs.google.com/document/d/1Wei8YfmKGutkdIL8uAl9iFQ-hewR6AzqTmxMVKyaFa4/edit?usp=sharing) of Report using my own data from Google Takeout and the YouTube API. Screenshots, showcasing the analysis and visualization process outcomes. It serves as a practical example to help users understand how the outcomes will be. Please note that the data in the document is my own and is used solely for demonstration purposes.

# Usage
To use this notebook, follow these steps:

Clone the repository to your local machine.<br>
Open the Jupyter notebook in your preferred environment (like JupyterLab or VSCode).<br>
Run the cells in sequence to see the data analysis and visualization in action.<br>

# Contributing
Contributions to this project are welcome. Please follow these steps to contribute:

Fork the repository.<br>
Create a new branch (git checkout -b feature-branch).<br>
Commit your changes (git commit -am 'Add some feature').<br>
Push to the branch (git push origin feature-branch).<br>
Create a new Pull Request.<br>

# License
This project is licensed under the MIT License - see the LICENSE file for details.

# Acknowledgments
Data from Google Takeout and YouTube API.<br>
Inspiration from various data science projects.
