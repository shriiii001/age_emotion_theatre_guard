 Emotion Detection using CNN (PyTorch)

This project detects facial emotions using a basic CNN trained on the FER-2013 dataset.

 Dataset
- FER-2013 (7 classes): Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

 Model
- Custom CNN built from scratch using PyTorch.
- Trained for 10 epochs.

 Performance Metrics
- Accuracy: Achieved >70% validation accuracy
- Includes confusion matrix, precision, and recall (saved in `metrics_report.txt`)

 Files
- `emotion_face_model_training.ipynb` : Training notebook
- `emotion_face_model.pth` : Saved model weights
- `metrics_report.txt` : Classification report
- `requirements.txt` : List of dependencies

 Setup
 bash
pip install -r requirements.txt

 Run
Open the notebook and run all cells sequentially.
