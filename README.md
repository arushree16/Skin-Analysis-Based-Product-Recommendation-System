Here’s an updated version of the README that reflects your file structure and situation:  

---

# Skin Analysis System  

A deep learning-based project designed to analyze skin type, acne levels, and skin tone from images and provide personalized skincare recommendations.  

## Features  
- **Skin Type Detection**: Classifies skin as oily, dry, combination, or normal.  
- **Acne Detection**: Identifies acne severity levels ranging from 0 to 2.  
- **Skin Tone Prediction**: Determines skin tone categories to aid product recommendations.  
- **Recommender System**: Suggests skincare products tailored to the user’s needs based on the analysis.  

## Project Structure  
```  
├── Skin_Tone.ipynb            # Notebook for skin tone classification  
├── acnedetection.ipynb        # Notebook for acne level detection  
├── half_proj.ipynb            # Combined implementation for skin analysis  
├── project_cvdl.ipynb         # Implementation of the computer vision deep learning model  
├── recommender.ipynb          # Recommender system notebook  
├── skin-types-final.ipynb     # Notebook for skin type classification  
└── model.keras                # Saved combined model (not uploaded due to size)  
```  

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: TensorFlow, Keras, OpenCV, NumPy, Pandas  
- **Models Used**:  
  - MobileNetV2: For skin type classification  
  - InceptionV3: For acne detection and skin tone prediction  

## How to Use  
1. Clone the repository:  
   ```bash  
   git clone <repository_url>  
   cd skin-analysis-system  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run individual notebooks (`.ipynb`) for skin type, acne level, and skin tone analysis.  
4. Use the `recommender.ipynb` to generate product recommendations based on predictions.  

## Dataset  
The project uses image datasets for skin type, acne severity, and skin tone classification. Preprocessing steps include resizing and normalization to match model requirements.  

## Limitations  
- The model file `model.keras` is not included due to size constraints.  
- Users must load the individual notebooks to access functionalities.  

## Future Work  
- Optimize the model for real-time analysis and deployment.  
- Create a lightweight version of `model.keras` for easy sharing and usage.  
- Develop a user-friendly web or mobile interface.  

