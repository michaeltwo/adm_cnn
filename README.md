# adm_cnn

Original raw dataset:
https://www.kaggle.com/competitions/birdclef-2025/data?select=train_soundscapes

INFO_535_ADM_Preprocessing and INFO_535_ADM_CNN are codes to handle data preprocessing and modeling.
mel_spectrograms are the data after preproessing.
Including one report and one slides

Folder Structure:
```
INFO_535_ADM_Slides.pptx/
INFO_535_Applied_Data_Mining_Report.pdf/
INFO_535_ADM_CNN.ipynb/
INFO_535_ADM_Preprocessing.ipynb
README.md
taxonomy.csv/   
mel_spectrograms/ 
├── 21038/               
│   ├── iNat65519_chirp.npy
│   └── iNat65519_denoised.npy
│   └── iNat65519_denoised_hpss.npy
│   └── iNat65519_denoised_median_filter.npy
│   └── iNat65519_denoised_spectral.npy
├── 21116/                 
│   ├── iNat65520_chirp.npy
│   └── iNat65520_denoised.npy
│   └── iNat65520_denoised_hpss.npy
│   └── iNat65520_denoised_median_filter.npy
│   └── iNat65520_denoised_spectral.npy
├── 21211/
│   └── XC882885_chirp.npy
│   └── XC882885_denoised.npy
...
```
