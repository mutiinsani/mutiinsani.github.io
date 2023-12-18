## Tampered Image Detection

### Project description

Train a model to perform image tampering detection. Image tampering consist of:
- Splicing
- Copy move

We use this model as an attempt to detect whether an image uploaded is tampered or not. 
Tampered detection is a way to verify originality of a picture. This project focus on splicing method.

### Dataset
- CASIA dataset
- Images of ID (KTP / SIM / KITAS) 

### Process 
General process in detecting tampered image:
1. Image preparation: resizing image to (128 x 128) or (64x64)
2. Extracting features
    - Error Level Analysis (ELA)
    - Local Binary Pattern (LBP)
    - YCbCr
    - PRNU
3. Creating neural network layers
4. Model Evaluation

### Details and code samples
1. Image preparation
2. Features
3. Neural network layers
4. Evaluation



