# BrainGAN

This project showcases the use of a Generative Adversarial Network built with PyTorch to create synthetic medical images.

## Project Aim

The goal was to train a GAN on a dataset of healthy brain CT scans from the [DeepStroke dataset](https://www.kaggle.com/datasets/huseyincavus/deepstroke). The objective was for the AI model to learn the fundamental patterns, textures, and structures of this complex medical data in order to generate entirely new, plausible examples.

## Workflow

1. **Data Loading:** A dataset of brain CT scans was loaded and preprocessed.
2. **Multi-GPU Training:** A custom GAN was trained. The process involved overcoming common GAN training challenges by implementing advanced stabilization techniques.
3. **Image Generation:** The final, trained Generator was used to create synthetic images.

## Results

The GAN learned the distribution of the training data. It is now capable of generating synthetic brain scans that capture the key anatomical features of real CT images. This demonstrates the model's ability to understand and replicate complex, real-world visual data.

## License

This project is licensed under the MIT License. See the **LICENSE** file for details.
