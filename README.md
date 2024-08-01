# AI Blog Generator

## Description
AI Blog Generator is a Django-based web application that generates blog content from YouTube video URLs. 
Utilizing OpenAI for content generation, AssemblyAI for transcription, and PostgreSQL for database management, the application provides a seamless way to convert video content into informative blog posts.

## Features
- Input a YouTube URL to generate a summary.
- Utilizes OpenAI for content generation.
- Uses AssemblyAI for video transcription.
- Stores data in a PostgreSQL database.
- User-friendly interface for easy interaction.


## AI Blog Generator Application Structure:

  AI_Blog_Generator/
│
├── ai_blog_generator/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── blog/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   └── forms.py
│
├── templates/
│   ├── all-blogs.html
│   ├── blog-details.html
│   ├── index.html
│   ├── login/Signup.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── scripts.js
│   
│
├── manage.py
├── requirements.txt

