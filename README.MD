# TRISTAR TAKEHOME ASSESSMENT

## How to run code:

- Clone the repository: https://github.com/NTPRuntime/Tristar_Takehome_Assessment.git
- Have python 3.10.12 or 3.10.X installed (X = 12+)
- Create the python virtual environment. Since I am on Linux (Ubuntu22.04) I used `python3 -m venv .pytorch_venv`
- Activate the virtual environment by running `source .pytorch_venv/bin/activate`
- Install pip requirements by running `pip3 install -r pip_requirements.txt`
- View outputs saved within the Jupyter notebooks of prior training session; or run notebooks to verify code runs properly.
- Ensure the dataset is unzipped with the `metal_plate` directory folder at the same level as the jupyter notebooks otherwise the paths will break. View below for text layout.

```
Main_Directory
|
-> classifier.ipynb
-> fastai_classifier.ipynb
-> pip_requirements.txt
-> metal_plate
   |
   -> ground_truth/*
   -> test/*
   -> train/*
```

- NOTE: I used CUDA and my RTX 3070 to build the following models. The same can be run without an NVIDIA GPU but instead on the CPU; it will just take longer to run