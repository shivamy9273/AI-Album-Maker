# AI Face Album Maker

AI Face Album Maker is a Python-based application that automatically organizes a folder of photos into person-wise albums using AI-powered face recognition. It detects faces, extracts embeddings, clusters similar identities, and generates downloadable albums containing original images and a representative cropped face for each person.

Built with InsightFace, FAISS, OpenCV, and Gradio.

Execute on Google Colab.

🚀 Features

📸 Upload a folder of images
🧠 Detect and recognize faces using deep learning
🔗 Cluster images by identity using vector similarity
🗂️ Automatically create person-wise photo albums
🖼️ Save original images + one cropped face per person
📦 Download all albums as a ZIP file
🌐 Simple and interactive Gradio web interface

🛠️ Tech Stack

Python
InsightFace – Face detection & embeddings
FAISS – Fast similarity search and clustering
OpenCV – Image processing
NumPy
Gradio – Web UI
