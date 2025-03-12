# Introduction
Here is my python source code for QuickDraw - an online game developed by google. with my code, you could:

Run an app which you could draw in front of a camera (If you use laptop, your webcam will be used by default)
Run an app which you could draw on a canvas
# Mediapipe app
To use this app, you can use the hand that appears in front of the camera. When you're ready to draw, you hold your hand with one finger. The tip of that finger will be the tip of the pen. When you're done, you can open your hand to see the results. Want to stop drawing you press ESC.

(https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHVhYWZwZ2V6bWpuaXpmNnprNnJxeGt3ZndsZXhiYjE1MDl6dWd3ZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/m58x5h4QwBfOczB70t/giphy.gif)


# Bộ dữ liệu 
The dataset used for training my model could be found at [Quick Draw dataset] https://console.cloud.google.com/storage/browser/quickdraw_dataset/sketchrnn. Here I only picked up 20 files for 20 categories
# Training 
You need to download npy files corresponding to 20 classes my model used and store them in folder data. If you want to train your model with different list of categories, you only need to change the constant CLASSES at src/config.py and download necessary npz files. Then you could simply run python3 train.py
