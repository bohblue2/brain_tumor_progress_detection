# How to use
```
micromamba activate brain_tumor
pip install uv
micromamba install -c conda-forge dicom2nifti pydicom jupyter jupyterlab nibabel
uv pip install pytorch torchvision torchaudio
```

# How to download dataset
```
cd datasets
kaggle datasets download dschettler8845/brats-2021-task1
kaggle datasets download andrewmvd/brain-tumor-progression

unzip brain-tumor-progression.zip
mkdir -p BraTS2021_Training_Data && tar -xvf BraTS2021_Training_Data.tar -C BraTS2021_Training_Data
mkdir -p BraTS2021_00621 && tar -xvf BraTS2021_00621.tar -C BraTS2021_00621
mkdir -p BraTS2021_00495 && tar -xvf BraTS2021_00495.tar -C BraTS2021_00495
```