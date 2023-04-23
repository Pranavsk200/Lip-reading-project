# Lip-reading-project

The process being referred to here is a machine learning project that involves the recognition of spoken words from video inputs. The first step in this process is to read the video input, which is typically a sequence of frames captured from a camera or video file. To reduce the amount of data to be processed, the frames are converted into a compressed format known as Graphics Interchange Format (.gif).

Once the video input has been transformed into a gif format, it is passed to the machine learning model. This model has been trained on large amounts of data to identify spoken words from video inputs. The model processes the gif file and makes a prediction on what the spoken words are. The model utilizes advanced algorithms such as Conv3d(CNN algorithm), MaxPool3D and Long Short-Term Memory (LSTM) networks to make these predictions.

The objective of this machine learning project is to develop a real-time system that can accurately detect spoken words from video inputs even in the absence of audio, thereby ensuring its reliability.

# Technologies Used

* Python 3
* Pandas
* Matplotlib
* Jupyter Notebook
 
 # Installation 
 
 1. Clone this repository
 2. Install the required packages using the following command:
 
```python
pip install -r requirements.txt
```

# Usage 
1. Navigate to the app/streamlitapp.py in comand prompt or terminal
2. Run the application using following command:
```python
streamlit run streamlitapp.py
```

# Result
1. select the video you want to predict words 
2. The video is converted into .git formet then the wordes are perdicted 

# Conclusion

The machine learning project discussed here aims to create a robust and dependable system for recognizing spoken words from video inputs in real-time, without the need for audio. The process involves converting the video input into a compressed gif format, which is then passed to a trained machine learning model. The model utilizes advanced algorithms such as Conv3d, MaxPool3D, and LSTM networks to make accurate predictions on spoken words. The project's ultimate objective is to develop a reliable system that can accurately detect spoken words from video inputs, ensuring its dependability in various applications.
