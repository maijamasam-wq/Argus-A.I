# Argus AI

Advanced Deepfake Detection Technology

## Project Structure

```
Argus_A.I/
├── docs/                   # Documentation
├── models/                 # Trained ML models and training logs
├── scripts/                # Python training/inference scripts
├── webapp/                 # React Frontend
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── pages/         # Page components
│   │   └── styles/        # CSS/Tailwind
│   ├── public/            # Static assets
│   └── package.json       # Dependencies
├── requirements.txt        # Python dependencies
└── README.md              # This file
```

## Quick Links

- **[Frontend Documentation](webapp/README.md)** - React + Vite + Three.js
- **[Architecture Plan](docs/frontend-redesign-plan.md)** - Design specifications

## Getting Started

### Frontend
```bash
cd webapp
npm install
npm run dev
```

### Backend (Flask)
```bash
# Activate virtual environment
.\venv\Scripts\activate

# Run Flask app
python webapp/backend.py
```

## Technologies

- **Frontend**: React 18, Vite, Tailwind CSS, Three.js, GSAP, Framer Motion
- **Backend**: Flask, TensorFlow/Keras, Xception Model
- **ML**: Deep learning for image classification

## Features

- 🔍 Deepfake detection (88.67% accuracy)
- 🎨 Beautiful animated UI
- 🎭 3D particle backgrounds
- ⚡ Smooth scroll animations
- 📱 Fully responsive
