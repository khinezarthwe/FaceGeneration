### Face Generation

#### Introduction
- In this project, you'll use generative adversarial networks to generate new images of faces.

#### Getting the project files
- The project files can be found in our public GitHub repo, in the project-face-generation folder.

```
git clone https://github.com/udacity/deep-learning-v2-pytorch.git
```

#### Suggestions to Make Your Project Stand Out!
- Create a deeper model and use it to generate larger (say 128x128) images of faces.
- Read existing literature to see if you can use padding and normalization techniques to generate higher-resolution images.
- Implement a learning rate that evolves over time as they did in this [CycleGAN Github repo](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix).
- See if you can extend this model and use a CycleGAN to learn to swap different kinds of faces. 
For example, learn a mapping between faces that have and do not have eye/lip makeup, as they did [in this paper](https://gfx.cs.princeton.edu/pubs/Chang_2018_PAS/Chang-CVPR-2018.pdf).