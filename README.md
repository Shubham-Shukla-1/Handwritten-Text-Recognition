<p>Handwritten recognition, also known as handwriting recognition or handwriting OCR (Optical Character Recognition), is the process of converting handwritten text into digital text. It involves using algorithms and machine learning techniques to analyze and interpret handwritten characters or symbols and translate them into machine-readable text. Handwritten recognition systems are employed in various applications, including digitizing handwritten documents, assisting in automatic form processing, enabling handwritten input in digital devices, and aiding in postal address recognition, among others. These systems typically involve preprocessing steps like image segmentation and feature extraction, followed by classification using pattern recognition or neural network-based approaches.</p>

# Handwritten-Text-Recognition
<br>
## How can I use?
1. Install the related libraries
> This project uses deep learning related libraries, go check them out if 
> you want to modify the code
```
pip install mltu
pip install numpy
pip install matplotlib
pip install pandas
pip install opencv-python
pip install Flask
pip install pillow
pip install tqdm
pip install librosa
```
2. Clone the original files in git bash
```
git clone https://github.com/Shubham-Shukla-1/Handwritten-Text-Recognition.git
```
3. Run the home.py, and access the local server address to try it!
```
python project_src/home.py
```



## File Descriptions
```
├── project_src
    ├── Model_development 
        ├── handweitten_to_digit    # place to do Nerual Network model 
        ├── line_segmentation       # place to do OpenCV operations
    ├── static                      # place to save temp data files and CSS files
    ├── templates                   # place to save HTML files 
    ├── test_image                  # place to save the .jpg file for QuickScan test
    ├── home.py                     # @@place to start the ScriptScan@@
├── readme_file_src
├── Environments.txt                # environments needed to run the program
├── LICENSE.txt 
├── README.md 
```
