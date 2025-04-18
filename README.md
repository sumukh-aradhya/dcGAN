# dcGAN
## 🪐 GalaxyGAN: DCGAN Meets Deep Space

Welcome to **GalaxyGAN** — a Deep Convolutional GAN (DCGAN) that dreams up galaxies while sipping TensorFlow

This repo includes:
- `dcgan.ipynb`: your interactive Colab lab for training, tweaking, and visualizing
- `dcgan.py`: your script mode sidekick — full pipeline, start to finish

> **Dataset not included.**  
> Reach out to me to get access to `Galaxy10_DECals2.h5`

### This repo includes:
- A DCGAN built with **TensorFlow/Keras**
- Custom training loop to generate deep space imagery
- Model saving, TensorBoard logging, and image generation
- GPU check — because time is precious

### Setup

```bash
pip install tensorflow h5py matplotlib scikit-learn
```

Drop the `Galaxy10_DECals2.h5` file in the same directory when you get it

### Run It

**Notebook**  
Interactive & visual:
```bash
jupyter notebook dcgan.ipynb
```

**Script**  
Full training pipeline:
```bash
python dcgan.py
```

Make sure you have these folders created: `checkpoint/`, `logs/`, `models/`, `output/`

### Output

Watch the GAN generate new galaxies each epoch:
```
output/generated_img_###.png
```

### Final Words

AI that makes galaxies. What’s next? Nebula NFTs?
