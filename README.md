# GlossoIdent
Tongue Print Based Forensic Individual Identification System
# GlossoIdent
### Tongue Print Based Forensic Individual Identification System

A multi-feature tongue print biometric identification system 
using ORB, SSIM, Histogram, LBP, HOG, Hash and Shape features 
with automated forensic PDF report generation.

## Methods Used
- ORB Feature Matching (25%)
- SSIM Structural Similarity (20%)
- Histogram Correlation (15%)
- LBP Texture Analysis (15%)
- HOG Gradient Features (10%)
- Perceptual Hash (10%)
- Shape Features (5%)

## Folder Structure
tongue_database/ → registered images
tongue_test/     → test image
forensic_report/ → PDF report output

## Run
pip install opencv-python scikit-image matplotlib numpy
python main.py
