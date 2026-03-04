# image-identifier
Uses your webcam to identify objects in frame into classes

For this project, we used OPEN cv and a model called ssd_mobile net for configuring our model, which was trained on the COCO dataset with 80 classes. We also used a frozen graph that converted all pieces of data into constants. We tested our model by capturing images, then switched to webcams.  The video is resized to be 320 x 320, and the pixels are normalized as we apply the prediction and confidence thresholds to the code. Then we render the labels and boxes. Open CV helped by handling the memory, and by loading the model for us.  Open CV also handled the resizing of pixels for us. Each frame of the video is treated as an image or frame.  So the same process for images occurs each frame constantly.  

<img width="676" height="555" alt="Screenshot 2026-03-02 142517" src="https://github.com/user-attachments/assets/518a72f8-5894-4ec3-8e94-c589de93511e" />
