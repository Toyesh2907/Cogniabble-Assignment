# Object Tracking with Deep SORT

This notebook was run in **Google Colab** using a **T4 GPU** for model training.

## Steps to Run the Notebook

1. **Clone Required Git Repo**:  
   The first cell in the notebook clones the necessary repository for the Deep SORT algorithm, which was used for object tracking.

2. **Run Each Cell**:  
   After cloning the repository, run each cell in the notebook sequentially.

3. **Importing Dataset via Roboflow**:  
   When you reach the dataset importing cell, note that you will need to provide your own Roboflow API key.

4. **Optional Model Training**:  
   If you do not wish to train the model, you can **skip the `train.py` cell** and proceed with the other cells for inference.

5. **Running Inference**:  
   In the inference cell (`predict.py`), provide the path to the video file you want to process.  
   A sample video file from Google Drive has been used for demonstration.

## Notes

- Ensure you have your Roboflow API key ready for dataset access.
- If you're only interested in running inference, simply skip the training step.
