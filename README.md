# Unraveling Brainstem Deformations in Joubert Syndrome: A Statistical Shape Analysis of MRI-Derived Structures


Code repository under construction for the provisionally accepted MICCAI 2025 paper: *Unraveling Brainstem Deformation in Joubert Syndrome: A Statistical Shape Analysis of MRI-Derived Structures*


🧑‍💻️ **Installation and Requirements**

Our project requires the creation of a virtual environment with python version 3.11.9. The pipeline requires the installation 
of [pyFM](https://github.com/RobinMagnet/pyFM) , as specified in requirements.txt.

```bash 
conda create -n SSA-brainstem python=3.11.9   # create conda virtual environment
conda activate SSA-brainstem
pip install -r requirements.txt  # install other necessary libraries via pip
```

📝 **Dataset**

Under folder 'Dataset', data used in the project are available and divided in three subfolders.
- '*original*': contains the raw .obj shapes of brainstem at original resolution as obtained by segmentation masks from MRI;
- '*remeshed*': contains preprocessed .obj shapes at 3K resolution after cleaning and remeshing procedure via [ReMatching](https://github.com/filthynobleman/rematching)
- '*bm*': contains .mat files scaling back from low to high resolution shapes



For privacy reasons, all data are anonymized and provided with basic information in 'info_subjects.xlsx'.\
After approval, data will also be available in Zenodo and [BOARD](https://board.unimib.it/research-data/)

⚙️ **Pipeline**


🙏 **Acknowledgement**



🎓 **Attribution**


**License** 🚀
This project is licensed under the MIT License.