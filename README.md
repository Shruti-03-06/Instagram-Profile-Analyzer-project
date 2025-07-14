
📊 Instagram Profile Analyzer
A Python GUI application that analyzes Instagram public profiles using Instaloader and Instagram API. It provides insights like:

Follower count, followees, biography, and profile picture

Engagement metrics (likes/comments) for the last 5 posts

A modern dashboard using ttkbootstrap

Visual charts for followers, posts, and post performance

🔧 Features
✅ Fetch Instagram public profile data
✅ Display last 5 post insights
✅ Visualize profile performance in bar charts
✅ Simulate follower growth
✅ Engagement rate calculation
✅ Built using Tkinter, Instaloader, Matplotlib, and ttkbootstrap




Install dependencies:

pip install -r requirements.txt
Run the GUI:

python app_gui.py
Or to launch the dashboard version:

python analyzer_dashboard.py

🔐 Authentication
To scrape private profiles, login using your own credentials in analyzer_dashboard.py

Use Instaloader.login() with caution. Store credentials securely.

Avoid scraping if not compliant with Instagram's terms

📁 File Structure
Copy code
Instagram-Profile-Analyzer/
├── app_gui.py
├── analyzer_dashboard.py
├── requirements.txt
├── README.md
🧠 Future Ideas
Export data to CSV

Show follower trends over time

Add profile picture downloader

OAuth-based access token for full API support

👩‍💻 Author
Shruti Jain

