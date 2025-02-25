# 🌍 Travel Recommender

## Overview
This project is a travel recommendation system that helps users find the best places to visit in different cities based on their interests. The system filters locations by country, city, and category, and also provides weather information. It uses **machine learning**, **text similarity analysis**, and **APIs** to improve recommendations.

The application is built using **Streamlit** for the user interface and integrates data from multiple sources, including **Overpass API** and **Google Places API**.

---

## Project Files
- **app.py**: The main Streamlit application that allows users to select a country, city, and preferences to get personalized travel recommendations.
- **style.css**: Custom styles to enhance the layout of the Streamlit interface.
- **data/**: Folder containing pre-processed datasets for different categories (hotels, nature, events, restaurants, tourist attractions, transit, and weather).
- **travel recommender.zip/**.

---

## Features
✅ **Country & City Selection**: Users first choose a country, then a city.  
✅ **Category Preferences**: Users can specify interests (e.g., nature, restaurants, stadiums).  
✅ **Smart Filtering**: Recommendations are personalized based on user preferences.  
✅ **Weather Data**: Displays current weather conditions for the selected city.  
✅ **Interactive UI**: Built with **Streamlit** for an intuitive and smooth experience.  

---

## Technologies Used

| Technique               | Description |
|-------------------------|-------------|
| **Pandas**             | Data manipulation and filtering |
| **TF-IDF Vectorizer**  | Text transformation for similarity calculation |
| **Cosine Similarity**  | Ranking locations based on textual similarity |
| **Streamlit**          | Web application framework for interactive UI |
| **APIs (Overpass, Google Places)** | Fetching real-time data about locations |
| **Custom CSS**         | Improving the UI and layout customization |

---

## Machine Learning Techniques

- **Natural Language Processing (NLP)**: Used for **text similarity analysis** of place descriptions.
- **TF-IDF + Cosine Similarity**: Finds similar locations based on their description.
- **Recommendation System**: Filtering places based on user preferences.

---

## Future Improvements 
- **Better AI Integration**: Improve recommendations using machine learning.
- **User History Personalization**: Adapt recommendations based on past selections.
- **More API Integrations**: Enhance data sources for richer insights.
