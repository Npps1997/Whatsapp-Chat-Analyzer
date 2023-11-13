# WhatsApp Chat Analyzer

Website Link:  https://whatsapp-chat-analyzer-ifczgl2atnc5yk4hztcj2y.streamlit.app/

WhatsApp Chat Analyzer is a Streamlit web application designed to analyze and visualize WhatsApp chat data. This application provides various statistics, sentiment analysis, timelines, and visualizations to gain insights into your chat history.

## Screenshots

### Home Page
![Screenshot (55)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/1cc783f0-32fd-474a-87de-b4a9973c4b11)


The home page allows users to upload their WhatsApp chat export file using the file uploader in the sidebar.

### Overall Statistics
![Screenshot (56)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/27059022-68dd-48f3-858e-a6bfbe6724d9)


After uploading the chat file, users can select a user for analysis and click the "Show Analysis" button. The application displays top statistics such as total messages, total words, media shared, and links shared.

### Sentiment Analysis
![Screenshot (57)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/79f5a093-6962-450e-94a7-22c47df64a77)


The sentiment analysis section provides visual insights into the sentiment scores of messages, either for the overall chat or for a specific user.

### Monthly Timeline
![Screenshot (58)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/7cb0bc54-c60d-41e0-bb5b-91f2922492f1)


The monthly timeline section shows a line plot of monthly message counts over time.

### Daily Timeline
![Screenshot (60)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/71a8baaa-3baf-4dcc-929d-a1d4a26c14c0)


The daily timeline section displays a line plot of daily message counts.

### Activity Maps
![Screenshot (61)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/00033865-4d92-433a-bcde-86de800ca4d6)


The activity maps section includes bar charts highlighting the most active day and month in the chat.

### Weekly Activity Map
![Screenshot (62)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/eb416cf0-fed0-423a-b115-897a5ab32c82)


The weekly activity map section visualizes the distribution of messages throughout the week.

### Most Busy Users
![Screenshot (63)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/36b2f580-cc96-4cee-bd44-a7c2dff0c9d6)


For group-level analysis, the most busy users section displays a bar chart of the users with the highest message counts.


### Wordcloud and Most Common Words
![Screenshot (64)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/f95da92f-0b5e-461b-9e7b-7db699f25051)

![Screenshot (65)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/8efa3b63-a1e5-4d3e-9671-9108b0a97319)


The Wordcloud section generates a visual representation of word frequencies, while the Most Common Words section presents a bar chart of the most frequently used words.

### Emoji Analysis
![Screenshot (66)](https://github.com/Npps1997/Whatsapp-Chat-Analyzer/assets/96871890/f5822a2c-11e4-4bbb-81f8-6f013439ec28)


The Emoji Analysis section provides a dataframe and a pie chart showing the distribution of emojis used in the chat.

## Installation

### Clone the repository:
   ```bash
   git clone https://github.com/Npps1997/Whatsapp-Chat-Analyzer.git
   cd whatsapp-chat-analyzer
   pip install -r requirements.txt
   streamlit run app.py
   ```

## Usage

1. **Upload Chat Data:**
   - Use the file uploader in the sidebar to upload your WhatsApp chat export file.

2. **Select User for Analysis:**
   - After uploading the chat file, select a user from the dropdown menu for analysis.

3. **Show Analysis:**
   - Click the "Show Analysis" button to generate insights and visualizations based on the selected user.

4. **Explore Sections:**
   - Navigate through various sections, including overall statistics, sentiment analysis, timelines, activity maps, and more.

5. **Discover Insights:**
   - Explore visualizations and statistics to gain insights into message patterns, sentiment, and user activity.

## Dependencies

- **Streamlit:** A Python library for creating web applications.
- **Matplotlib:** A 2D plotting library for creating static, animated, and interactive visualizations.
- **Seaborn:** A statistical data visualization library based on Matplotlib.
- **nltk:** A natural language processing library for text analysis.
- **pandas:** A powerful data manipulation and analysis library.
- **emoji:** A Python library for working with emoji characters.
- **urlextract:** A Python library for extracting URLs from text.
- **wordcloud:** A Python library for creating word clouds.

## Contributing

Contributions are welcome! If you have ideas for improvements, open an issue or create a pull request.

## Acknowledgments

Special thanks to the developers of Streamlit and the libraries used in this project.
