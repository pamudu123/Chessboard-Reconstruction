<p align="center">

  <h1 align="center">Chess Board Reconstrauction</h3>

  <p align="center">
    Using Computer-Vision
    <br />
  </p>
</p>

##  Chessborad Corners Detection

### 1: Keypoint Detection Algorithm

<p align="center">
<img src="Resources/chess_corners.png" width="500">
</p>

This algorithm is built on top of the ResNet architecture, which is a robust and powerful architecture known for its ability to learn complex representations of visual data. 
The keypoint detection algorithm utilizes the features learned by the ResNet architecture to accurately 
detect the corners of the board, making it an effective solution for this task.

<p align="center">
<img src="Resources/model.png" width="500">
</p>


### 2: Warp Perspective Transformation 

<p align="center">
<img src="Resources/warp_img.png" width="500">
</p>

### 3: Train Chess Peace Detection Model
#### YOLOv8

<p align="center">
<img src="Resources/yolo.png" width="700">
</p>

### 4: Find Positions of Pieces
<p align="center">
<img src="Resources/detect_board.png" width="350">
</p>

