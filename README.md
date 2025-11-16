# AllergenDetect

A web application that helps users identify allergens in food products by scanning barcodes and analyzing ingredient lists.

## Overview

AllergenDetect uses computer vision and natural language processing to scan food product barcodes, extract ingredient information, and detect the presence of common allergens. This tool is designed to help people with allergies, intolerances, and dietary restrictions quickly and accurately determine if a product is safe for consumption.

## Why This Matters

Being able to easily identify exactly what allergens or other compounds are in a food is essential for the well-being of people who have allergies, intolerances, and/or dietary restrictions that prevent them from consuming certain substances. Many ingredients can have multiple names, and foods produced in different places may have varying labeling structures; therefore, a tool like this would greatly assist individuals trying to identify if a product contains ingredients they can’t have (e.g., gluten, dairy).

## MVP Features

### Core Functionality
Dropdown for a few specific allergens (peanuts, tree nuts, gluten, dairy, shellfish)
Able to upload images from your camera and have those processed
Extra: take photos through the web app?
Once the photo is processed, the output states whether the allergen appears to be present or not present, and if it is, lists the specific ingredients that the model is picking up


### Stretch Goals
- In-app camera functionality for real-time scanning
- Multi-language support for international products
- User allergy profiles for personalized scanning

## Tech Stack

### Front-end
Build with React and TypeScript
### Backend 
Uses PyTorch, Keras, or TF model?
I'm not sure how to connect this to the front end yet. Do I need to deploy it with Docker or Kubernetes?
Probably going to publish through Vercel



