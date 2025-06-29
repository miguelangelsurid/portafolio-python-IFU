# project-python-IFU

This work will serve as an introduction to handling integral field spectroscopy data. To do this, we will start with a data cube from which we will extract information and obtain various images of the galaxy. These images will include the galaxy at a specific wavelength, spectra from different regions of the galaxy, and images in the r and i bands along with the corresponding r-i color image.

## Data

The data used in this work can be downloaded in this link: https://www.dropbox.com/scl/fo/amsoy4i3lkmyorozpb81u/ABQ8Z7djP_Ks1o1xq4Qe01g?rlkey=zafi4cm9ngenpbc172yo46xqj&st=jgyagc30&dl=0](https://www.dropbox.com/scl/fo/x1kr9w0p5y498wiqehezr/AEIKpK4Np4YC_AkTTwGTViY?rlkey=tomexhbfnkmdv2eg03qu5p5wr&st=31hytzxj&dl=0

## You need to have (Requirements)

- Python 3.10

- NumPy

- Matplotlib 

- Astropy 

- Photutils

- LaCosmic 

- SciPy 

- Jupyter Notebook

Install using:

```bash
pip install -r requirements.txt
```

## Structure
```
├── Introduction_to_IFU250324.ipynb # Notebook 
├── requirements.txt # Requirements
└── README.md
```

## What you need to do

- Create an environment:
```
python3 -m venv envAstro
```
- Activate it:
source envAstro/bin/activate

- Install requirements inside environment
  
- Download the data

- Execute cells on jupyter lab

## Results

We have successfully obtained the data from the data cube and used it to analyze the galaxy image across different wavelengths and bands, as well as to analyze spectra from different regions.

With the color image, we identified regions of star formation and interstellar dust, and with the H-alpha image, in addition to locating the HII regions, we were able to obtain the redshift for each zone of the galaxy, allowing us to observe the effect of rotation on it. Finally, in the different spectra, we managed to identify the emission lines for the HII regions.

## Author

Miguel Ángel Susillo Ridao

Linkedin: www.linkedin.com/in/miguelangelsurid
