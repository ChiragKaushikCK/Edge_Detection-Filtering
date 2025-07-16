<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</div>

<h1 align="center" style="color: #4A90E2; font-family: 'Segoe UI', sans-serif; font-size: 3.5em; text-shadow: 2px 2px 4px rgba(0,0,0,0.2);">
  <br>
  <a href="https://github.com/your-username/edge-detection-techniques">
    <img src="https://placehold.co/600x200/4A90E2/FFFFFF?text=Edge+Detection+Project" alt="Edge Detection Project Banner" style="border-radius: 15px; box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);">
  </a>
  <br>
  🌟 Edge Detection Techniques with OpenCV 🌟
  <br>
</h1>

<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 0 auto; line-height: 1.6;">
  Welcome to the **Edge Detection Techniques** project! This Jupyter Notebook demonstrates the power of edge detection using OpenCV in Python, showcasing methods like Sobel edge detection and Fourier Transform-based techniques. Whether you're a computer vision enthusiast or a curious learner, this project is designed to help you explore and visualize edge detection in images with a touch of flair! ✨
</p>

<br>

<details style="background-color: #F0F8FF; border-left: 5px solid #4A90E2; padding: 15px; border-radius: 8px; margin: 20px auto; max-width: 700px; box-shadow: 0 2px 10px rgba(0,0,0,0.1);">
  <summary style="font-size: 1.3em; font-weight: bold; color: #333; cursor: pointer;">Table of Contents</summary>
  <ol style="list-style-type: decimal; padding-left: 25px; line-height: 1.8;">
    <li><a href="#project-overview" style="color: #4A90E2; text-decoration: none;">🚀 Project Overview</a></li>
    <li><a href="#features" style="color: #4A90E2; text-decoration: none;">🎯 Features</a></li>
    <li><a href="#prerequisites" style="color: #4A90E2; text-decoration: none;">🛠️ Prerequisites</a></li>
    <li><a href="#how-to-run" style="color: #4A90E2; text-decoration: none;">📋 How to Run</a></li>
    <li><a href="#example-output" style="color: #4A90E2; text-decoration: none;">📷 Example Output</a></li>
    <li><a href="#code-breakdown" style="color: #4A90E2; text-decoration: none;">🧠 Code Breakdown</a></li>
    <li><a href="#customization-ideas" style="color: #4A90E2; text-decoration: none;">🌈 Customization Ideas</a></li>
    <li><a href="#troubleshooting" style="color: #4A90E2; text-decoration: none;">🐛 Troubleshooting</a></li>
    <li><a href="#resources" style="color: #4A90E2; text-decoration: none;">📚 Resources</a></li>
    <li><a href="#contribute" style="color: #4A90E2; text-decoration: none;">🎉 Contribute</a></li>
  </ol>
</details>

---

<h2 id="project-overview" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🚀 Project Overview
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  This project is a hands-on exploration of edge detection techniques applied to grayscale images. It leverages <strong style="color: #007BFF;">OpenCV</strong> and <strong style="color: #007BFF;">NumPy</strong> to process images, detect edges, and apply transformations like the Inverse Fourier Transform. The notebook includes clear code snippets for Sobel edge detection and frequency-domain filtering, with vibrant visual outputs to make the results pop! 🎨
</p>

---

<h2 id="features" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🎯 Features
</h2>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #E6F7FF; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #007BFF;">✨ Sobel Edge Detection:</strong> Detects edges using Sobel operators in both X and Y directions, combining them for a comprehensive edge map.
  </li>
  <li style="margin-bottom: 15px; background-color: #E6F7FF; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #007BFF;">📏 Thresholding:</strong> Applies binary thresholding to enhance edge visibility and create clean, sharp outlines.
  </li>
  <li style="margin-bottom: 15px; background-color: #E6F7FF; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #007BFF;">🔄 Fourier Transform:</strong> Explores frequency-domain image processing with Inverse Fourier Transform to reconstruct images, revealing hidden patterns.
  </li>
  <li style="margin-bottom: 15px; background-color: #E6F7FF; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #007BFF;">🖼️ Visualizations:</strong> Displays original and processed images side-by-side for easy and impactful comparison.
  </li>
  <li style="margin-bottom: 15px; background-color: #E6F7FF; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #007BFF;">✍️ Interactive Code:</strong> Well-commented Jupyter Notebook cells ensure clarity and facilitate an engaging learning experience.
  </li>
</ul>

---

<h2 id="prerequisites" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🛠️ Prerequisites
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  To run this project, ensure you have the following installed:
</p>
<ul style="list-style-type: disc; padding-left: 20px; font-size: 1.1em; color: #444;">
  <li><strong style="color: #007BFF;">Python 3.x</strong></li>
  <li><strong style="color: #007BFF;">Jupyter Notebook</strong></li>
  <li>Required Libraries:
    <pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code>pip install opencv-python numpy</code></pre>
  </li>
  <li><strong style="color: #007BFF;">Google Colab</strong> (optional, for running the notebook in the cloud)</li>
</ul>
<p style="background-color: #FFF3E0; border-left: 5px solid #FF9800; padding: 10px 15px; border-radius: 8px; font-size: 0.95em; color: #666; margin-top: 20px;">
  💡 <strong>Note:</strong> The notebook uses <code>cv2_imshow</code> from <code>google.colab.patches</code> for displaying images in Colab. For local environments, replace <code>cv2_imshow</code> with <code>cv2.imshow</code> or use Matplotlib for visualization.
</p>

---

<h2 id="how-to-run" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📋 How to Run
</h2>
<ol style="list-style-type: decimal; padding-left: 20px; font-size: 1.1em; color: #444; line-height: 1.8;">
  <li style="margin-bottom: 10px;">
    <strong style="color: #007BFF;">Clone or Download the Notebook:</strong>
    <p style="margin-top: 5px;">Download <code>Edge_Detection_Techniques.ipynb</code> from this repository.</p>
    <p style="margin-top: 5px;">Alternatively, open it directly in <a href="https://colab.research.google.com/" style="color: #4A90E2; text-decoration: none;">Google Colab</a>.</p>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #007BFF;">Install Dependencies:</strong>
    <pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code>pip install opencv-python numpy</code></pre>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #007BFF;">Prepare an Image:</strong>
    <p style="margin-top: 5px;">Place an image (e.g., <code>Sample_Img.webp</code>) in the same directory as the notebook or update the file path in the code.</p>
    <p style="margin-top: 5px;">Ensure the image is grayscale-compatible or convert it within the notebook.</p>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #007BFF;">Run the Notebook:</strong>
    <p style="margin-top: 5px;">Open <code>Edge_Detection_Techniques.ipynb</code> in Jupyter or Colab.</p>
    <p style="margin-top: 5px;">Execute each cell sequentially to see the magic happen! ✨</p>
    <p style="margin-top: 5px;">The notebook will display the original image, Sobel edge-detected images, and Fourier-transformed outputs.</p>
  </li>
  <li style="margin-bottom: 10px;">
    <strong style="color: #007BFF;">Explore and Experiment:</strong>
    <p style="margin-top: 5px;">Tweak parameters like <code>threshold_value</code> or Sobel kernel size (<code>ksize</code>) to see different effects.</p>
    <p style="margin-top: 5px;">Try different images to test the robustness of the edge detection techniques.</p>
  </li>
</ol>

---

<h2 id="example-output" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📷 Example Output
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Below is a sneak peek of what you’ll see when you run the notebook:
</p>

<div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 30px;">
  <div style="flex: 1 1 300px; text-align: center; background-color: #F8F8F8; padding: 15px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
    <h3 style="color: #007BFF; font-size: 1.5em; margin-bottom: 10px;">Original Image:</h3>
    <img src="https://placehold.co/300x200/A0A0A0/FFFFFF?text=Original+Image" alt="Original Image Placeholder" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  </div>
  <div style="flex: 1 1 300px; text-align: center; background-color: #F8F8F8; padding: 15px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
    <h3 style="color: #007BFF; font-size: 1.5em; margin-bottom: 10px;">Sobel Edge Detection:</h3>
    <img src="https://placehold.co/300x200/FF5733/FFFFFF?text=Sobel+Edges" alt="Sobel Edge Detection Placeholder" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  </div>
  <div style="flex: 1 1 300px; text-align: center; background-color: #F8F8F8; padding: 15px; border-radius: 10px; box-shadow: 0 4px 15px rgba(0,0,0,0.1);">
    <h3 style="color: #007BFF; font-size: 1.5em; margin-bottom: 10px;">Fourier Transform Result:</h3>
    <img src="https://placehold.co/300x200/33FF57/FFFFFF?text=Fourier+Result" alt="Fourier Transform Result Placeholder" style="width: 100%; height: auto; border-radius: 8px; border: 1px solid #ddd;">
  </div>
</div>
<p style="background-color: #FFF3E0; border-left: 5px solid #FF9800; padding: 10px 15px; border-radius: 8px; font-size: 0.95em; color: #666; margin-top: 20px; text-align: center;">
  💡 <strong>Tip:</strong> The actual images in the notebook are dynamic and depend on your input image!
</p>

---

<h2 id="code-breakdown" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🧠 Code Breakdown
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Here’s a quick overview of the key sections in the notebook:
</p>

<h3 style="color: #007BFF; font-size: 1.8em; margin-top: 25px;">Import Libraries:</h3>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">import</span> <span style="color: #9CDCFE;">cv2</span>
<span style="color: #569CD6;">import</span> <span style="color: #9CDCFE;">numpy</span> <span style="color: #569CD6;">as</span> <span style="color: #9CDCFE;">np</span>
<span style="color: #569CD6;">from</span> <span style="color: #9CDCFE;">google.colab.patches</span> <span style="color: #569CD6;">import</span> <span style="color: #9CDCFE;">cv2_imshow</span></code></pre>

<h3 style="color: #007BFF; font-size: 1.8em; margin-top: 25px;">Sobel Edge Detection:</h3>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Applies Sobel operators to detect edges in X and Y directions, combines results using weighted addition, and applies binary thresholding.
</p>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #9CDCFE;">sobel_x</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">cv2.Sobel</span>(<span style="color: #9CDCFE;">image</span>, <span style="color: #569CD6;">cv2.CV_64F</span>, <span style="color: #B5CEA8;">1</span>, <span style="color: #B5CEA8;">0</span>, <span style="color: #9CDCFE;">ksize</span><span style="color: #CE9178;">=</span><span style="color: #B5CEA8;">3</span>)
<span style="color: #9CDCFE;">sobel_y</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">cv2.Sobel</span>(<span style="color: #9CDCFE;">image</span>, <span style="color: #569CD6;">cv2.CV_64F</span>, <span style="color: #B5CEA8;">0</span>, <span style="color: #B5CEA8;">1</span>, <span style="color: #9CDCFE;">ksize</span><span style="color: #CE9178;">=</span><span style="color: #B5CEA8;">3</span>)
<span style="color: #9CDCFE;">sobel_combined</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">cv2.addWeighted</span>(<span style="color: #9CDCFE;">sobel_x</span>, <span style="color: #B5CEA8;">0.5</span>, <span style="color: #9CDCFE;">sobel_y</span>, <span style="color: #B5CEA8;">0.5</span>, <span style="color: #B5CEA8;">0</span>)
<span style="color: #9CDCFE;">_</span>, <span style="color: #9CDCFE;">sobel_threshold</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">cv2.threshold</span>(<span style="color: #9CDCFE;">sobel_combined</span>, <span style="color: #B5CEA8;">100</span>, <span style="color: #B5CEA8;">255</span>, <span style="color: #569CD6;">cv2.THRESH_BINARY</span>)</code></pre>

<h3 style="color: #007BFF; font-size: 1.8em; margin-top: 25px;">Inverse Fourier Transform:</h3>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Performs frequency-domain processing to reconstruct the image.
</p>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #9CDCFE;">f_ishift</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">np.fft.ifft2</span>(<span style="color: #9CDCFE;">fshift</span>)
<span style="color: #9CDCFE;">img_back</span> <span style="color: #CE9178;">=</span> <span style="color: #569CD6;">np.abs</span>(<span style="color: #569CD6;">np.fft.ifft2</span>(<span style="color: #9CDCFE;">f_ishift</span>))</code></pre>

<h3 style="color: #007BFF; font-size: 1.8em; margin-top: 25px;">Visualization:</h3>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Displays the original and processed images for comparison.
</p>
<pre style="background-color: #2D2D2D; color: #E0E0E0; padding: 15px; border-radius: 8px; overflow-x: auto; font-family: 'Fira Code', monospace; font-size: 0.95em; box-shadow: 0 2px 10px rgba(0,0,0,0.15);"><code><span style="color: #569CD6;">cv2_imshow</span>(<span style="color: #9CDCFE;">image</span>)
<span style="color: #569CD6;">cv2_imshow</span>(<span style="color: #9CDCFE;">img_back</span>)</code></pre>

---

<h2 id="customization-ideas" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🌈 Customization Ideas
</h2>
<p style="font-size: 1.1em; color: #444; line-height: 1.6;">
  Want to take it further? Here are some fun ways to enhance the project:
</p>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">✨ Experiment with Thresholds:</strong> Adjust the <code>threshold_value</code> to fine-tune edge detection sensitivity and discover subtle details.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🔍 Try Different Filters:</strong> Add Canny or Laplacian edge detection for a comprehensive comparison of various techniques.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🎨 Color Images:</strong> Extend the code to process color images by applying edge detection to each channel independently.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🎛️ Interactive Widgets:</strong> Use Jupyter widgets to create sliders for real-time parameter tuning and dynamic exploration.
  </li>
  <li style="margin-bottom: 15px; background-color: #E0F7FA; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #00BCD4;">🎬 Animation Effects:</strong> Create a video or GIF of the edge detection process for a cool visual effect and engaging presentation.
  </li>
</ul>

---

<h2 id="troubleshooting" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🐛 Troubleshooting
</h2>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 15px; background-color: #FFEBEE; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #D32F2F;">❌ Image Not Found:</strong> Ensure the image file path is correct (e.g., <code>/content/Sample_Img.webp</code> in Colab). Double-check file name and extension.
  </li>
  <li style="margin-bottom: 15px; background-color: #FFEBEE; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #D32F2F;">🖥️ Display Issues:</strong> If <code>cv2_imshow</code> fails, try using <code>matplotlib.pyplot.imshow</code> for visualization. Remember to convert BGR to RGB if using Matplotlib.
  </li>
  <li style="margin-bottom: 15px; background-color: #FFEBEE; padding: 10px 15px; border-radius: 8px; box-shadow: 0 1px 5px rgba(0,0,0,0.05);">
    <strong style="color: #D32F2F;">📉 Fourier Transform Errors:</strong> Verify that <code>fshift</code> is defined before applying the inverse Fourier transform. The notebook may require additional cells to compute the forward Fourier transform (e.g., <code>dft = cv2.dft(np.float32(image), flags=cv2.DFT_COMPLEX_OUTPUT)</code> and <code>fshift = np.fft.fftshift(dft)</code>).
  </li>
</ul>

---

<h2 id="resources" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  📚 Resources
</h2>
<ul style="list-style-type: none; padding: 0; font-size: 1.1em; color: #444;">
  <li style="margin-bottom: 10px;"><a href="https://docs.opencv.org/4.x/" style="color: #4A90E2; text-decoration: none; font-weight: bold;">OpenCV Documentation</a></li>
  <li style="margin-bottom: 10px;"><a href="https://numpy.org/doc/stable/" style="color: #4A90E2; text-decoration: none; font-weight: bold;">NumPy Documentation</a></li>
  <li style="margin-bottom: 10px;"><a href="https://docs.opencv.org/4.x/d8/d01/tutorial_discrete_fourier_transform.html" style="color: #4A90E2; text-decoration: none; font-weight: bold;">Understanding Fourier Transform in Image Processing (OpenCV)</a></li>
</ul>

---

<h2 id="contribute" style="color: #333; font-family: 'Segoe UI', sans-serif; font-size: 2.5em; border-bottom: 3px solid #FFD700; padding-bottom: 10px;">
  🎉 Contribute
</h2>
<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 0 auto; line-height: 1.6;">
  Feel free to <strong style="color: #007BFF;">fork this project</strong>, <strong style="color: #007BFF;">submit pull requests</strong>, or <strong style="color: #007BFF;">open issues</strong> for suggestions! Let’s make edge detection even more exciting together! 🚀
</p>
<p align="center" style="font-size: 1.2em; color: #555; max-width: 800px; margin: 15px auto 0; line-height: 1.6;">
  <strong style="color: #FFD700;">Star this repo</strong> if you find it helpful, and share your edge-detected masterpieces with the community! 🌟
</p>
<p align="center" style="font-size: 1em; color: #777; margin-top: 30px;">
  Created with 💖 by the Chirag
</p>
