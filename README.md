# Deep-learning-based-Image-Dehazing
ES-CCGAN is an unsupervised deep-learning model for removing haze from remote-sensing images. It uses CycleGAN with DenseNet-based generators, edge-sharpening loss, and a fine-tuned VGG16 network to produce clear and sharp dehazed images.

🚀 Features

Unsupervised dehazing (no paired data needed)

DenseNet blocks for texture restoration

Edge-sharpening loss for clearer boundaries

Perceptual loss using VGG16

Works on custom hazy/clear datasets

🧠 Architecture

Two generators (Hazy→Clear, Clear→Hazy)

Two discriminators

Combined losses: adversarial, cycle, perceptual, edge-sharpening

🛠️ Training

50 epochs, batch size 1

Adam optimizer (LR 0.0002)

Dataset: unpaired hazy & clear images (256×256)

▶️ Output

Input a hazy image → Model generates a clean, sharp, haze-free image suitable for remote-sensing analysis.
