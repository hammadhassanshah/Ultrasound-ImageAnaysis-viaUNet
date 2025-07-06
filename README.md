# Ultrasound-Image-Segmentation
# Data Processing: 
- Begin by installing necessary libraries. Follow that up with downloading, processing, and extracting ultrasound data from kaggle

# Model Initiation:
- Initialize the U-Net Model with specific parameters, perform preprocessing on the input data and build a U-Net architecture with downsampling and upsampling.
- Following that, batch the dataset and then train it on the ultrasound images using the batch_size parameter in .fit()

# Model Optimization:
- Optimize the model initially through the Adam framework then SGD, followed by an Adam Decay and then SGD Decay Framework 
- Run KLD and DICE loss functions separately
- Measure accuracy and efficiency at each step and do comparisons to understand differences

# Contribution:
- Each of us made valuable contributions to this process. Emma was responsible for bringing and processing data, Yuna conducted experiments on the model, and Hammad was responsible for bringing different elements together.
