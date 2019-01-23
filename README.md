# Capsule-Networks-on-MNIST

CNN are very effective in Image Classification tasks but they have certain fallacies.One such fallacy is unability to detect the spatial orientation or the geometry of the object in the images which hampers their accuracy.Capsule networks were designed to get rid of this fallacy.

Let us consider a very simple and non-technical example. Imagine a face. What are the components? We have the face oval, two eyes, a nose and a mouth. For a CNN, a mere presence of these objects can be a very strong indicator to consider that there is a face in the image. Orientational and relative spatial relationships between these components are not very important to a CNN.

Whereas a capsule net preserves this geometry in a similar fashion our brain works.
Another benefit of the capsule approach is that it is capable of learning to achieve state-of-the art performance by only using a fraction of the data that a CNN would use 


The CapsNet has 2 parts: encoder and decoder. The first 3 layers are encoder, and the second 3 are decoder:
Layer 1. Convolutional layer
Layer 2. PrimaryCaps layer
Layer 3. DigitCaps layer
Layer 4. Fully connected #1
Layer 5. Fully connected #2
Layer 6. Fully connected #3
