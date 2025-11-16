# AllergenDetect

A web application that helps users identify allergens in food products by scanning barcodes and analyzing ingredient lists.

## Overview

AllergenDetect uses computer vision and natural language processing to scan food product barcodes, extract ingredient information, and detect the presence of common allergens. This tool is designed to help people with allergies, intolerances, and dietary restrictions quickly and accurately determine if a product is safe for consumption.

## Why This Matters

Managing food allergies and dietary restrictions can be challenging:
- **Multiple ingredient names**: Allergens can appear under various chemical or alternative names
- **Inconsistent labeling**: Different countries and manufacturers use different labeling standards
- **Time-consuming**: Reading and interpreting ingredient lists takes time and expertise
- **Health critical**: Accidental exposure to allergens can have serious health consequences

AllergenDetect simplifies this process by automatically identifying allergens and highlighting specific ingredients of concern.

## MVP Features

### Core Functionality
- **Allergen Detection**: Support for 5 common allergens
  - Peanuts
  - Tree nuts
  - Gluten
  - Dairy
  - Shellfish
- **Image Upload**: Upload photos of food labels from your device
- **Detailed Results**: 
  - Clear indication of allergen presence/absence
  - List of specific ingredients that contain the detected allergen
  - Confidence levels for detection

### Stretch Goals
- In-app camera functionality for real-time scanning
- Multi-language support for international products
- User allergy profiles for personalized scanning

## Tech Stack

### Frontend
- **Framework**: React with TypeScript
- **Deployment**: Vercel

### Backend
- **ML Framework**: TensorFlow/Keras or PyTorch (TBD)
- **OCR**: Tesseract.js or Google Cloud Vision API
- **API**: REST API (Node.js/Express or Python/FastAPI)
- **Containerization**: Docker (for model deployment)

### Infrastructure Considerations
- Model hosting options: AWS Lambda, Google Cloud Run, or Kubernetes
- Database: PostgreSQL or MongoDB (if needed for user data/allergen database)

## Project Timeline

### Week 1: Planning & Proposal
- [x] Define project scope and MVP features
- [x] Research tech stack options
- [ ] Finalize proposal document
- [ ] Set up project repository and development environment

### Week 2: Foundation
- [ ] Build initial React frontend framework
- [ ] Design UI/UX mockups
- [ ] Research and select OCR/ML models for:
  - Barcode scanning
  - Text extraction from images
  - Ingredient parsing
- [ ] Set up backend API structure

### Week 3: Core Development
- [ ] Implement image upload functionality
- [ ] Integrate OCR for ingredient extraction
- [ ] Build allergen detection logic
- [ ] Create allergen database/mapping system
- [ ] Connect frontend to backend API
- [ ] Implement results display interface

### Week 4: Testing & Polish
- [ ] End-to-end testing with real food labels
- [ ] Bug fixes and error handling
- [ ] Performance optimization
- [ ] Documentation and code cleanup
- [ ] Prepare demo and presentation
- [ ] Deploy to production environment

## Task Division

### Partner A: Frontend Development
- React application structure
- User interface components
- Image upload and camera integration
- Results display and user experience
- Frontend-backend integration

### Partner B: Backend & ML
- Model selection and training/fine-tuning
- OCR implementation
- Allergen detection algorithm
- API development
- Database design and implementation
- Deployment and containerization

*Note: These are flexible guidelines - we'll collaborate on all aspects as needed*

## Getting Started

### Prerequisites
```bash
Node.js >= 18.x
Python >= 3.9 (for backend)
npm or yarn
```

### Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/allergen-detect.git

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
pip install -r requirements.txt
```

### Development
```bash
# Run frontend
npm run dev

# Run backend (in separate terminal)
python app.py
```

## Contributing

This is a course project with limited scope, but we welcome suggestions and feedback!

## Open Questions

- [ ] Best approach for connecting ML model to frontend (serverless vs. container)?
- [ ] OCR accuracy with various lighting conditions and label formats
- [ ] How to handle ambiguous ingredient names?
- [ ] Privacy considerations for image uploads

## License

TBD

## Acknowledgments

- Course instructors and TAs
- Open-source ML model communities
- Allergen databases and food safety resources

---

**Project Status**: In Development

**Timeline**: 4 weeks (Proposal due Week 1)
