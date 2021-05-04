# Action-Recognition

Optimized Action Recognition to enable faster inferences using just images instead of videos.

## Drawbacks of Current Techniques: 

- Action Recognition has been a compute heavy process where a video is analysed frame by frame using a Recurrent Neural Network and then have their results across time combined to detect the action performed. 
- Apart from RNNs making the process compute heavy, it is also time consuming for a larger set of videos. 

## Ideas for improvement:

- Can a video be converted to a smaller format?
- Is there another way to extract temporal information? 

## Solutions to these issues:

- Eliminate use of videos by bringing in images
- Utilize Optical Flow

The notebooks contain snippets on how the data was processed and sent to the model and how well the model learned and performed. Further improvements include:

- Improving frame selection
- Training on large data using Unsupervised Learning 
- Supporting newer model architectures
