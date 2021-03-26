# DetectionModel
Saved Model and Tensorflow.js layer formats

Source: https://medium.com/swlh/build-custom-object-detection-web-application-using-tensorflow-js-d1664f96a18b

1. Index.html:  Import **TensorFlow.js 3.3.0** and define the video stream.
*Note: use the same TensorFlow.js version to convert the model and run in web app. I used 3.3.0 for the model conversion to layer formats from inference graph.
2. Load the detection model: we use **tf.loadGraphModel** to load files stored in the web_model folder in an async manner (**script.js **: Line 64)
   Image size set to 320 --> Line: 91
   Threshold: 50%
   score: 50%
3. Run the app on a local server in IDE like Atom or publish it on Netlify directly from Github
