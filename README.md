# WhatsApp Chat Analyzer Project

## Table of Contents
- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [Challenges and Solutions](#challenges-and-solutions)
- [Results and Learning](#results-and-learning)
- [Why It’s Useful](#why-its-useful)
- [Setup Instructions](#setup-instructions)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project analyzes WhatsApp chat exports to uncover meaningful insights about communication patterns, user activity, and chat sentiment. It offers data visualization and user-friendly analytics to help users better understand their chat interactions.

## How It Works
- **Data Import:** Upload exported WhatsApp chat files in `.txt` format.
- **Analysis:** The tool processes and visualizes various aspects of the chat data, including:
  - Total messages and word counts.
  - Media and links shared.
  - Most active days and months.
  - User engagement trends and heatmaps.
  - Sentiment analysis and emoji usage.

## Challenges and Solutions
- **Data Cleaning:** Handling different chat export formats was challenging. Custom parsing logic was developed to handle variations in data format.
- **Visualization:** Choosing meaningful visualizations to present chat activity was crucial. Graphs and heatmaps were used to make insights easy to interpret.

## Results and Learning
- The tool provided actionable insights, such as identifying the most active participants and understanding chat trends.
- Learned valuable skills in data preprocessing, visualization, and sentiment analysis.

## Why It’s Useful
- This project demonstrates proficiency in working with text data and building analytical tools.
- It highlights skills in data visualization, sentiment analysis, and real-world data processing.

## Setup Instructions

### Prerequisites
- Python 3.x
- Streamlit (`pip install streamlit`)

### Steps to Run the Analyzer
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
   cd whatsapp-chat-analyzer
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```
4. Upload your WhatsApp chat export file and view the analysis.

## Features
| Feature                      | Description                                     |
|------------------------------|-------------------------------------------------|
| Total Messages Analysis      | Counts the number of messages                  |
| User Engagement              | Identifies the most active users               |
| Activity Heatmap             | Shows weekly activity patterns                 |
| Word Cloud                   | Visualizes the most common words               |
| Sentiment Analysis           | Analyzes message sentiment                     |
| Emoji Analysis               | Displays emoji usage patterns                  |

## Technologies Used
- **Python:** Core programming language
- **Pandas:** Data processing and analysis
- **Matplotlib & Seaborn:** Data visualization
- **Streamlit:** Web application framework

## Contributing
1. Fork the project.
2. Create your feature branch:
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/AmazingFeature
   ```
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See `LICENSE` for more information.
