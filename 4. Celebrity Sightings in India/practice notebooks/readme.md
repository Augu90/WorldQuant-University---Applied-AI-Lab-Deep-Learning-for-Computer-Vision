# Face Detection and Recognition with Mary Kom Interview Video

In this project, I worked on performing **face detection** and **face recognition** using a video of an interview with Indian Olympic boxer **Mary Kom**. My goal was to use state-of-the-art pre-trained models to detect and recognize faces, and then create a simple web app that allows users to test face recognition on new images.

## Project Overview

In this project, I:

1. Selected frames from the interview video to focus on Mary Kom and her interviewer.
2. Used a pre-trained **Multi-task Cascaded Convolutional Network (MTCNN)** to detect faces in these frames.
3. Created **face embeddings** for each person using the **Inception-ResNet V1 model**.
4. Built a library of known face embeddings.
5. Developed functionality to recognize faces in new images by comparing them to the embeddings library.
6. Wrapped everything into a **Flask app** that lets users upload an image and perform face recognition.

## What I Learned

Through this project, I learned how to:

- Use pre-trained **MTCNN** and **Inception-ResNet V1** models from `facenet_pytorch`.
- Extract **face bounding boxes** and cropped faces from images and videos.
- Generate **face embeddings** and construct a library of known faces.
- Compare new images to the embeddings library to determine if a face is recognized.
- Build a **Flask app** to make the face recognition system interactive and user-friendly.
