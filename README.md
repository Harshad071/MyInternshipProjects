# Object/Image Detection using YOLOv7

This project utilizes the YOLOv7 model for efficient and accurate object/image detection. Follow the steps below to set up and run the project on your local device.

---

## Prerequisites

- Python 3.8+
- YOLOv7 repository (download from [YOLOv7 GitHub](https://github.com/WongKinYiu/yolov7))
- Required libraries: Install dependencies mentioned in the YOLOv7 repository.

---

## Setup and Installation

1. **Download YOLOv7 Repository**  
   Clone or download the YOLOv7 repository from the official [GitHub repository](https://github.com/WongKinYiu/yolov7).

2. **Add Project Files**  
   Paste the following files into the YOLOv7 directory:  
   - `flaskaap.py`
   - `flaskaap1.py`
   - `flaskaap2.py`
   - `flaskaap3.py`
   - `hubconfCustom.py`
   - `hubconfcustomweb.py`
   - `yolov7-tiny.pt` (weights file)

3. **Update Weights**  
   Ensure the model uses `yolov7-tiny.pt` as the weights file. Replace any existing weight file references in the code.

4. **Add HTML Templates**  
   Paste the three provided HTML files into the `templates` directory within the YOLOv7 project folder.

---

## Running the Project

1. **Start the Application**  
   Run the Flask application using the provided Python scripts (`flaskaap.py`, `flaskaap1.py`, etc.). Use any of the scripts as per your setup requirements.

   ```bash
   python flaskaap.py
