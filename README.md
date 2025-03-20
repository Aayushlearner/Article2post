# Article2post


Article2Post 📰➡️📱

AI-Powered News Article & LinkedIn Post Generator

Article2Post is a cutting-edge Streamlit-based application that generates high-quality news articles and instantly transforms them into engaging LinkedIn posts. Powered by Groq for AI-driven content creation and SerpApi for real-time web search, Article2Post streamlines your content workflow, saving you time and boosting your online presence.

🚀 Features

✅ AI-Powered Journalism:

Generates comprehensive, well-structured news articles on any topic.
Includes proper attribution, quotes, and relevant statistics.
✅ LinkedIn Post Generator:

Converts articles into concise, professional LinkedIn posts.
Includes hashtags, line breaks, and a CTA for engagement.
✅ Real-Time Information Retrieval:

Uses SerpApi to search for recent and relevant information.
✅ User-Friendly Interface:

Simple Streamlit UI with interactive buttons.
One-click copy to clipboard for LinkedIn posts.
🛠️ Tech Stack

Streamlit: Frontend interface
Groq: AI model for article and LinkedIn post generation
SerpApi: Real-time web search
Python: Backend logic
Pyperclip: Clipboard functionality
dotenv: For environment variables
🔧 Installation

Clone the repository
git clone <repository-url>
cd article2post
Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies
pip install -r requirements.txt
Set up environment variables
Create a .env file in the root directory.
Add your API keys:
GROQ_API_KEY=your_groq_api_key
SERPER_API_KEY=your_serper_api_key
Run the app
streamlit run app.py
✅ Usage

Enter a topic in the input field.
Click "Generate" to create the article.
Click "Generate LinkedIn Post" to convert the article into a LinkedIn post.
Use the "Copy to Clipboard" button to easily share the post on LinkedIn.
🚀 Future Enhancements

Add support for different content formats (blogs, reports, etc.).
Improve LinkedIn post customization with tone and style options.
Add multilingual support.

