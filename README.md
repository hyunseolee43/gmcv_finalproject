# Project Research Code - GMCV

## Contents

├── README.md                       this file \
├── checkpoints/    \
│   ├── phase1_vae                        Phase 1 β-VAE (frozen for Phase 2) \
│   └── phase2_latent_diffusion           Phase 2 LDM (channel-concat conditioning) \
├── data_manifests/    \
│   ├── slices_manifest_full_150.csv                       \
│   ├── slices_manifest_full_200.csv                       \
│   └── slices_manifest_full_300.csv                       \
├── 0_data_preprocessing.ipynb            Data Preprocessing notebook \
├── 1_phase1_vae.ipynb                    Phase 1 VAE \
├── 2_phase2_latent_diffusion.ipynb       Phase 2 Diffusion \
└── 3_ablation_study.ipynb \\


## Dataset link
Link for the dataset can be found here: [Drive link to Yale-Brain-Mets-Longitudinal preprocessed dataset](https://drive.google.com/drive/folders/1P8plBX1Wg4lkbfLYbpzDtgNteDBDDOxO?usp=sharing)