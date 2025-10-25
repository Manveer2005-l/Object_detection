🧠 Object Detection using Mask R-CNN








This project implements Object Detection and Instance Segmentation using Mask R-CNN, a powerful deep learning architecture capable of detecting and segmenting multiple objects in an image.
The model identifies each object, draws bounding boxes, and overlays pixel-level masks — allowing fine-grained detection for real-world use cases such as autonomous systems, surveillance, and visual analytics.

🚀 Features

Detects multiple object classes (e.g., people, cars, animals, everyday items)

Produces bounding boxes, class labels, and segmentation masks

Built using pre-trained COCO weights for high accuracy and transfer learning efficiency

Capable of real-time inference on static images or short video clips

Visualizes detection outputs with confidence scores

💡 Key Highlights

Model: Used Mask R-CNN pre-trained on the COCO dataset (80 object categories)

Frameworks: Implemented with TensorFlow, OpenCV, and Matplotlib

Post-Processing: Applied Non-Maximum Suppression (NMS) to eliminate overlapping boxes

Performance: High accuracy on unseen images with clear segmentation boundaries

Visualization: Generated detection overlays combining masks and bounding boxes for clarity

🧠 Tech Stack

Language: Python 3.13

Libraries: TensorFlow | OpenCV | NumPy | Matplotlib | imutils

IDE: Jupyter Notebook / VS Code

⚙️ Installation
git clone https://github.com/manveersingh1048/Object-Detection.git
cd Object-Detection
pip install -r requirements.txt

🧩 Usage

To run object detection on an image:

python detect_objects.py --image input.jpg


To run on a video:

python detect_video.py --video sample.mp4

Sample Output
Input Image	Detection Result

	

(Each object is outlined with a bounding box, segmentation mask, and label with confidence score.)

🏆 Results

Detected up to 15+ objects per frame with accurate class labels

Average inference time: ~0.25s per image on GPU

Robust performance on both day/night and low-contrast images

📄 License

This project is released under the MIT License — free for research and educational use.

👨‍💻 Author

Manveer Singh
Data Scientist | Machine Learning & AI Enthusiast
📧 manveersingh104807700@gmail.com
