# Django-news-portal
Responsive Django News Portal fetching live news from different categories using News API.
📰 News Portal - Django Web App
A responsive Django-based news application that fetches the latest news articles from around the world using NewsAPI.org.
Users can browse through different news categories like Technology, Business, Health, Sports, and more!

🚀 Features
🌎 Latest global news

📚 Multiple categories (Business, Entertainment, Health, Science, Sports, Technology)

📱 Responsive design (Mobile Friendly)

🎨 Eye-catching Navbar and Layout

🔥 Bootstrap 5 for modern styling

📡 Integrated with NewsAPI.org

🛠 Built With
Django - Backend Framework

Bootstrap 5 - Frontend Styling

NewsAPI.org - News Provider

🚀 Installation Instructions
Clone the repository

bash
Copy code
git clone https://github.com/your-username/django-news-portal.git
cd django-news-portal
Create a virtual environment and activate it

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies

bash
Copy code
pip install -r requirements.txt
Set your NewsAPI Key

Open news/views.py

Replace 'YOUR_NEWS_API_KEY' with your actual API key.

Run the server

bash
Copy code
python manage.py runserver
Visit

Open http://127.0.0.1:8000/ in your browser to view the app.

⚙️ Environment Variables
You need to set the following environment variables:

API_KEY = Your NewsAPI.org Key

(You can store it in .env file for better security.)

📄 License
This project is licensed under the MIT License.

✨ Acknowledgements
NewsAPI.org for the free news data.

Bootstrap for beautiful UI components.

Django Community ❤️
