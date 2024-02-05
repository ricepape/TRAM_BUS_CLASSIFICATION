This project will classify the bus and the tram using feature extraction, KNN and SVM model

Tram_Train: https://freesound.org/people/publictransport/packs/36726/, https://freesound.org/people/ali.abdelsalam/packs/36722/

Bus_Train: https://freesound.org/people/emmakyllikki/packs/36810/, https://freesound.org/people/glingden/packs/36807/

Tram_Test, Bus_Test: Our own recordings

Setting up the Environment:

```
conda create --name comp.sgn.120 python=3.11.3
conda activate comp.sgn.120
conda install numpy=1.26.2
pip install ipykernel --upgrade
conda install -c conda-forge ffmpeg
pip install pydub==0.25.1
pip install tqdm==4.66.1
pip install librosa==0.10.1
pip install matplotlib==3.7.2
pip install scikit-learn==1.3.2
pip install scipy==1.11.4 
pip install pandas==2.1.4
```
