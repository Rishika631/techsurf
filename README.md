# Digital Asset Management (DAM) App
The Digital Asset Management (DAM) app is a full-stack web application developed using Streamlit. It empowers users to manage and manipulate digital images efficiently. The app offers a range of features, including image transformation, AI-powered image analysis, image resizing with AI analysis, built in drawing canvas and image optimization and also store all the changes made in the images as logs in the backend so that the user can go back and see changes, revert back to a particular unedited picture, for collabaration it can be helpful to see who did what changes and many more4 uses of logging the editing of images.

## Deployed website link: https://techsurfrishika.streamlit.app/
## Live video demo link: https://drive.google.com/file/d/1x7OlDUPK88rCkIYkFvCLYnU0niap28wt/view?usp=sharing

# Table of Contents

 Features
 
 Tech Stack
 
 Installation
 
 How to Use

# Features
Image Transformation: Users can perform various image transformations, including cropping, rotating, applying focal points, enhancing brightness, overlaying images, and adding frames.

AI Analysis and Tagging: The app utilizes the CLIP model to analyze uploaded images and generate relevant tags based on their content, making image searching and organization easier.

Image Resize with AI Analysis: Users can resize images while preserving essential details. The AI analysis ensures that the resized images maintain their content integrity and quality.

Image Optimization: The app offers image optimization techniques, such as format conversion and compression, to enhance image performance and loading speed.

Drawing Canvas: Explore your creativity with a built-in drawing tool.

# Tech Stack
The app is built using the following technologies:

Streamlit: For the web application framework and user interface.

PyTorch and torchvision: For image processing and transformations.

PIL (Python Imaging Library): For image handling and manipulation.

Hugging Face Transformers: For utilizing the CLIP model for AI analysis.

OpenAI: For integrating the OpenAI GPT-2 model for image caption generation.

HTML,CSS,Javascript: For generating built in drawing canvas.

MongoDB: For storing generated captions and image tags.

# Installation
## Clone the repository to your local machine:
```ruby
git clone https://github.com/Rishika631/techsurf.git
```
## Go to techsurf directory
```ruby
cd techsurf
```
## Install requirements
```ruby
pip install -r requirements.txt
```
## Install streamlit in local system
```ruby
pip install streamlit
```

Note: Before running the application change openAI key and mongoDB URL with below instructions.
Set up the OpenAI API key:
Replace <APIKEY> in the main.py file with your actual OpenAI API key.

Set up MongoDB connection:
Replace the MongoDB connection string in the main.py file with your MongoDB connection string.

# How to Use
Run the Streamlit app:
```ruby
streamlit run app.py
```
The app will launch in your browser. Use the sidebar to select the desired function (Image Transformation, AI Analysis, Image Resize, or Image Optimization or drawing canvas) and follow the on-screen instructions to upload and manipulate images.

For AI Analysis and Image Captioning, make sure to provide the necessary API key and model authorization in the code.
