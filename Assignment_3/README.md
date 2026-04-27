Use Jupyter notebook. 
Upload images - content.jpg and style.jpg for Jupyter notebook 
Use in cell#63- load_image('content.jpg'), load_image('style.jpg', shape=content.shape[-2:]).to(device)
The Hyperparameters in cell#70 and #13
Changed the default style_weights. Uncomment the default values and comment the ones below if the image needs to be run with default balanced values.
    style_weights = {'conv1_1': 2.0,
                     'conv2_1': 1.5,
                     'conv3_1': 1.0,
                     'conv4_1': 0.5,
                     'conv5_1': 0.1}
Run all the cells 
