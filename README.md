# Noise-Removal-using-Filters-in-images
Noise Removal using Filters is an image processing project that applies Gaussian, Median, and Bilateral filters to remove noise from grayscale images. It effectively cleans Gaussian noise and Salt & Pepper noise, while also preserving important image details. The project includes performance evaluation using PSNR (Peak Signal-to-Noise Ratio) to compare filter effectiveness. 
# Installation :
pip install opencv-python numpy matplotlib

# Usage
->Run the main script: python noise_removal.py

->Run individual filters:
python gaussian_filter.py  
python median_filter.py  
python bilateral_filter.py 

->Compare results: python compare_results.py

->Analyze PSNR performance: python psnr_analysis.py
