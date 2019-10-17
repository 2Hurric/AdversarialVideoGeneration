## Adversarial Video Generation
This project was forked from [dyelax’s work](https://github.com/dyelax/Adversarial_Video_Generation) and immigrated to TensorFlow1.2 and Python3, in order to be compatible to GTX1080 or later version GPU.

Adversarial generation uses two networks – a generator and a discriminator – to improve the sharpness of generated images. Given the past four frames of video, the generator learns to generate accurate predictions for the next frame. Given either a generated or a real-world image, the discriminator learns to correctly classify between generated and real. The two networks "compete," with the generator attempting to fool the discriminator into classifying its output as real. This forces the generator to create frames that are very similar to what real frames in the domain might look like.

### Results
We collected the data from a basketball game and a video game Snake.

![](https://imgur.com/5oSLdit)        ![](https://imgur.com/y7es0M1)
The detailed results is shown at [here](https://docs.google.com/presentation/d/1dSCPw3_T-7nOAzeLDiZp9Sbr--sUO0bDb7_78sKT2_U/edit?usp=sharing). 