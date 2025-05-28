A machine learning-based binary voice classification system that can distinguish between two singers using audio feature extraction and Support Vector Machines (SVM).

# SVM Voice Recognition Model - Performance Matrix

## Model Overview
- **Model Type**: Support Vector Machine (SVM)
- **Task**: Binary Classification (Voice Recognition)
- **Classes**: Arijit, Lata
- **Training Samples**: 97
- **Testing Samples**: 42
- **Train-Test Split**: 70%-30%
- **Random State**: 42

## Performance Metrics

### Overall Accuracy
| Metric | Value | Percentage |
|--------|-------|------------|
| **Accuracy** | 0.93 | 92.9% |


## Sample Predictions Analysis

### Prediction Results
| Sample | Actual | Predicted | Correct |
|--------|--------|-----------|---------|
| 1 | Arijit | Arijit | ✅ |
| 2 | Arijit | Arijit | ✅ |
| 3 | Lata | Lata | ✅ |
| 4 | Arijit | Arijit | ✅ |
| 5 | Lata | Lata | ✅ |

## Model Performance Summary

### Strengths
- **High Accuracy**: 92.9% accuracy indicates strong overall performance
- **Consistent Predictions**: Sample predictions show correct classification
- **Balanced Classes**: Model appears to handle both voice types well


## PROJECT STRUCTURE 
voice-recognition/
│
├── binary_classification.py    # Main classification script
├── requirements.txt           # Python dependencies
├── README.md                 # Project documentation
│
└── dataset_5s/              # Audio dataset directory
    ├── singer1/             # First singer's audio files
    │   ├── song1.wav
    │   ├── song2.wav
    │   └── ...
    └── singer2/             # Second singer's audio files
        ├── song1.wav
        ├── song2.wav
        └── ...




        
