# Image Colorization Using Convolutional Neural Network


Image colorization is the process of assingning colors to a grayscale image to make it more aesthetically appealing and perceptually meaningful. These are recognized as sophisticated tasks than often require prior knowledge of image content and manual adjustments to achieve artefact-free quality. Also, since objects can have different colors, there are many possible ways to assign colors to pixels in an image, which means there is no unique solution to this problem.
Our final output is a colored image. We have a grayscale image for the input and we want to predict two color layers, the ab in Lab. To create the final color image we’ll include the L/grayscale image we used for the input. The result will be creating a Lab image.
