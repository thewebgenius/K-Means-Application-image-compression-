# K-Means-Application-image-compression-
Image compression using K-Means clustering. This project demonstrates color quantization by reducing an image to a fixed number of colors (K), achieving compression while preserving visual quality. #Python #MachineLearning #Clustering #KMeans #ImageProcessing

🖼️ Image Compression using K-Means

<br>📌 Overview</br>
This project demonstrates image compression through K-Means clustering.
The idea is to reduce the number of distinct colors in an image while preserving most of its visual quality.
Original image → thousands of colors 🎨
Compressed image → only K dominant colors (e.g., 16)
Applications: color quantization, storage reduction, preprocessing for computer vision tasks.

<br>🚀 Features</br>
Load an image from file or URL
Reshape into (num_pixels, 3) RGB format
Apply K-Means clustering to group similar colors
Replace each pixel with its cluster centroid
Compare original vs compressed image side by side

<br>📂 Requirements</br>
pip install numpy matplotlib scikit-learn scikit-image

<br>📊 Example Output</br>


<br>📖 Learnings</br>
K-Means can be used beyond numeric data — e.g., for images
Lower K → higher compression, lower quality
Higher K → closer to original, less compression

<br>🔗 References</br>
Scikit-learn KMeans
Color Quantization
