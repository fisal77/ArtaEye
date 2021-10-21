# ArtaEye

ArtaEye (Art and Eye) is web/mobile cam eye tracking to make beautiful draw, art work based on eye moves.

Originally a repo for doing facial recognition and matching an emoji to it, I've since hijacked it to hold my models and data collection and raw data for my eye tracking mouse. I use hough circles to perform pupil detection, and use a CNN on a bunch of data I collected. 

MLtracking.py contains the real-time mouse, run it to let the webcam control the mouse!

andyCNN.py loads all the data from the eyes/ and testeyes/ dirs to train the models

eyetrack.py collects the pupil data by moving your cursor around the screen and having you follow its tip around.

testEyes.py evaluates the models I've trained. 
