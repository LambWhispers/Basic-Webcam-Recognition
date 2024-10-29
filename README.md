# Basic Webcam Recognition

This is just a very basic Webcam Recognition program that uses Jupyter Notebook (Python). It can be used by everyone for some funny testing. 

## Installation

1. Download the file directly from GitHub, you can download through ZIP.
2. Use the file anywhere that could handle .ipynb files, you should use Jupyter Notebook. If you haven't installed Jupyter Notebook yet, then I recommended you to download it through [here.](https://jupyter.org/install)
3. Once you are ready, please give the info of your faces/recognitions by changing the code inside the file. Remember to place the information at the right directory. 

```python
# Load a sample picture and learn how to recognize it.
known_image = face_recognition.load_image_file("Lamb Whisper.jpg")
known_face_encoding = face_recognition.face_encodings(known_image)[0]

# Create arrays of known face encodings and their names
known_face_encodings = [known_face_encoding]
known_face_names = ["Lamb Whisper"]  # Add more as needed
```

4. Get you webcam ready, and test it out! It's pretty fun to test actually.

## Contributing

There is just only me, Lamb Whispers. 
![108906351_p2](https://github.com/user-attachments/assets/b539d123-e1ef-4663-8820-98dd0a905103)
