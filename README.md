# InstaFetch
InstaFetch is a sleek and efficient tool that allows users to fetch and display data from public Instagram accounts using their user IDs. Powered by Rapid API, it simplifies accessing public account information for analytics, insights, or personal use—all through a user-friendly interface.


# InstaFetch

**InstaFetch** is a Flask-based web application that allows users to fetch data from public Instagram accounts using a username or ID. The app utilizes the **RapidAPI Instagram Scraper API** to retrieve profile details, posts, and followers.

## Features
- Fetch public profile details including profile pictures.
- Retrieve recent posts with images and save them locally.
- Access a list of followers with details like username, full name, and privacy status.
- User-friendly interface to display fetched data dynamically.

## Prerequisites
- Python 3.7 or later
- Flask
- Requests
- A valid RapidAPI key for the Instagram Scraper API

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/InstaFetch.git
   cd InstaFetch

Install dependencies:
pip install -r requirements.txt

Set up your environment variables:
Add your RapidAPI key and host in app.py.

Start the application:
python app.py


Open your browser and navigate to:   http://127.0.0.1:5000/



How to Use
Enter the Instagram username or user ID of a public account.
Click the "Fetch Data" button to retrieve information.
View the fetched data on the homepage:
Profile details
Posts with images
Followers list (accessible via a separate tab).


File Structure
app.py: Main application logic.
templates/: HTML files for the UI.
static/: Stores images and JSON files.
images/: Contains downloaded images.
Data/: Contains followers' data in JSON format.


API Details
Instagram Scraper API: Used to fetch profile, posts, and followers' data.


Screenshots
Homepage: Fetch data by entering the Instagram username.
Followers List: Displayed in a separate tab.



Future Enhancements
Add support for displaying more detailed analytics.
Enhance the UI for a better user experience.
Integrate additional Instagram APIs for deeper insights.


License
This project is open-source and available under the MIT License.


###Let me know if you'd like to include additional sections or make changes!
