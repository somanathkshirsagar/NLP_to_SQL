# MySQL Python Chatbot with GPT-4 and Mistral AI

Welcome to the GitHub repository for our tutorial on building a natural language SQL chatbot using GPT-4! In this project, we will guide you through creating a chatbot capable of interpreting and responding to user queries in natural language, generating SQL queries dynamically, and retrieving results from a MySQL database. The project features a user-friendly interface powered by Streamlit, allowing users of all skill levels to engage effortlessly.

## Table of Contents
* [Features](#features)
* [How It Works](#how-it-works)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Acknowledgments](#acknowledgments)
* [Support](#support)

<a name="features"></a>
## Features
- Natural Language Processing (GPT-4)
- SQL Query Generation
- MySQL Database Integration
- User-Friendly Streamlit GUI
- Python-Based Implementation

<a name="how-it-works"></a>
## How It Works
Our chatbot takes a user's natural language query, translates it into a SQL query utilizing GPT-4, performs the query against a MySQL database, and returns the result back to the user in natural language format. Various stages of data handling and interactions with both OpenAI API and MySQL database occur smoothly within a Streamlit application.

![Chatbot Architecture](./docs/mysql-chains.png)

Refer to the [tutorial video](https://youtu.be/your-video-url) for a comprehensive understanding and walkthrough.

<a name="prerequisites"></a>
## Prerequisites
Before getting started, make sure you meet these prerequisites:
- Python Installed

To verify if Python is already installed, open the terminal and type `python --version`. If not, download and install the latest version of Python from their official website: https://www.python.org/downloads/.

<a name="installation"></a>
## Installation
Clone the repo:
```bash
git clone [repository-link]
cd [repository-directory]
