# Eye_face_tracker

RetinaFace is a state-of-the-art deep learning-based facial detection system for Python. Originally implemented using the MXNet framework, it has gained popularity for its accuracy in detecting faces and facial landmarks. A TensorFlow-based re-implementation by Stanislas Bertrand has further extended its accessibility. RetinaFace stands out for its superior accuracy and speed compared to other facial detection methods such as dlib, SSD, and MTCNN. Its efficient architecture makes it a preferred choice for applications where both precision and real-time processing are crucial.



## Features

- Accurate detection of faces and facial landmarks
- Efficient and fast processing
- Implementation in both MXNet and TensorFlow (note: this is the TensorFlow implementation.)



## Installation

- Create a virtual environment: (recommended)

Linux/macOS:

```bash
  # Create a virtual environment
    python3 -m venv venv

  # Activate the virtual environment
    source venv/bin/activate
  
```

 Windows:

```powershell
  # Create a virtual environment
    python -m venv venv

  # Activate the virtual environment
    venv\Scripts\activate
  
```

- Clone the repository:


```bash
  git clone https://github.com/Anandukc/Face_detection_retina_face.git
```





- Install RetinaFace:


```bash
  pip install retina-face
```

- Set the image path

  Modify the line ``` 
  img_path = "path to input image" ``` in the retina_face.py file to the path of ```input_img.jpg```

- Run the script:

```bash
  python retina_face.py
```


  



## output result

![Output Example](https://github.com/Anandukc/Face_detection_retina_face/raw/main/output_result.png)


## reference
https://github.com/serengil/retinaface
https://arxiv.org/pdf/1905.00641
