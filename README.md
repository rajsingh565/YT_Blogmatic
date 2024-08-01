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

## Technologies Used
- Django: Web framework used for building the application.
- OpenAI: Used for content generation.
- AssemblyAI: Used for transcribing video content.
- PostgreSQL: Database for storing user data and generated content.

## Quick Start

   1. Clone the repository:
      ```
      git clone https://github.com/rajsingh565/AI_Blog_Generator.git
      ```
   2. Navigate to the project directory:
      ```
      cd AI_Blog_Generator
      ```
   3. Create and activate a virtual environment:
      ```
      python -m venv venv
      source venv/bin/activate  # On Windows use `venv\Scripts\activate`
      ```

   4. Install the required dependencies:
      ```
      pip install -r requirements.txt
      ```
   
   5. Apply database migrations:
      ```
      python manage.py migrate
      ```

   6. Run the development server:
     ```
     python manage.py runserver
     ```
   

