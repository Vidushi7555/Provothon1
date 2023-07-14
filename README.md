# Route-Direction-in-AR



Adding the Feature "Real World Path Direction" by tapping on Map. GoogleMap will give us the direction to that location from user location then click on "ARView" & you will get the real-world path direction.

Also added "Reachability" for finding path in Google map.

-- Also added .mlmodel for route-detection. Initially trained the model using Convolutional Neural Network in TensorFlow, then convert the .h5 output into .mlmodel. Use it in the application. 

-- In ARFrame generates capturedImage which is the input to .mlmodel for detecting that model is present in the image or not.

-- This project combines both ARKit & CoreML.

The project can be used in calculating the path & mapping the (lat,lng) in real world co-ordinate system.
