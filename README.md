# ArtaEye

ArtaEye is web/mobile camera eye tracking to make beautiful drawing, artwork based on eye movements.
In this project, we target people with disabilities to create an artwork, we try to translate their feelings through their eyes into digital drawings.

Originally a repo for doing facial recognition and matching an emoji to it, I've since hijacked it to hold my models and data collection and raw data for my eye tracking mouse. I use hough circles to perform pupil detection, and use a CNN on a bunch of data I collected. 

MLtracking.py contains the real-time mouse, run it to let the webcam control the mouse!

andyCNN.py loads all the data from the eyes/ and testeyes/ dirs to train the models

eyetrack.py collects the pupil data by moving your cursor around the screen and having you follow its tip around.

testEyes.py evaluates the models I've trained. 


Link to face_recognition library: https://github.com/ageitgey/face_recognition

Site for drawing my mouse location: https://processing.org/examples/continuouslines.html