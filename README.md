
# White Christmas

A replication of White Christmas's black mirror episode, where everyone was grayed out as a punishment.

- Run a pre-trained Mask R-CNN model with Detectron2
- Filter unwanted predictions, and only extract the "person" class
- Randomly generate a gray noise and replace the segmented area with that noise
- Can run on both images and videos
## Results

![original image](https://user-images.githubusercontent.com/43171921/236634914-4a0df21c-e432-4898-9802-768738993370.jpg)
![masked image](https://user-images.githubusercontent.com/43171921/236634924-7c8668fe-11fb-47ed-bf0d-7661aea93e53.jpg)
## Running

- Install ```PyTorch``` if you don't already have it
- Run the ``` White_christmas.ipynb```
- Detectron2 will be installed automatically in the notebook