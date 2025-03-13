# FastAPI Image Summarization API with YSecret & OpenAI

This FastAPI project allows users to upload an image and receive a brief summary using OpenAI's API. The project securely fetches the OpenAI API key using **YSecret**.

## Features

🌟 Secure API key retrieval with YSecret
🌟 Image Processing using PIL
🌟 Image Encoding in Base64 format
🌟 OpenAI Integration for summarization
🌟 FastAPI-based asynchronous API

## Installation & Setup

1. Clone the Repository : 
   ~ git clone https://github.com/ysidm2025/ysecret_implementation.git
   ~ cd ysecret_implementation

2. Create a Virtual Environment :
   ~ python -m venv venv
   ~ source venv/bin/activate  # On Windows use: venv\Scripts\activate

3. Install Dependencies :
   ~ pip install -r requirements.txt

4. pip install ysecret-0.0.3.tar.gz
  
5. Set Up Environment Variables :
   ~ OPENAI_API_KEY=your_API_key

6. Inside image_routes :
   ~ s=secrets.get_secret_with_id(your_secret_id)

7. Inside venv\Lib\site-packages\ysecret\SecretManager.py
   ~ access_token = your_access_token_

## Usage

1. Start the FastAPI Server :
   ~ uvicorn main:app --reload
   ~ API will be available at: http://127.0.0.1:8000




