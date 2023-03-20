<div align="center">
    <h6>Environmental Data Science Book</h6>
</div>

<p align="center">
<img src="https://github.com/alan-turing-institute/environmental-ds-book/blob/master/book/figures/logo/logo.png?raw=True" alt="thumbnail" width="200"/>
</p>

<div align="center">
    <h1>Tree crown detection using DeepForest</h1>
</div>

<p align="center">
    <a href="https://github.com/eds-book-gallery/15d986da-2d7c-44fb-af71-700494485def/blob/main/LICENSE">
        <img alt="License" src="https://img.shields.io/badge/License-MIT-yellow.svg">
    </a>
    <a href="https://notebooks.gesis.org/binder/v2/gh/eds-book-gallery/15d986da-2d7c-44fb-af71-700494485def/main?labpath=notebook.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://github.com/eds-book-gallery/15d986da-2d7c-44fb-af71-700494485def/actions/workflows/render.yaml">
        <img alt="Render" src="https://github.com/eds-book-gallery/15d986da-2d7c-44fb-af71-700494485def/actions/workflows/render.yaml/badge.svg">
    </a>
    <br/>
</p>

<p align="center">
    <a href="https://w3id.org/ro-id/15d986da-2d7c-44fb-af71-700494485def">
        <img alt="RoHub" src="https://img.shields.io/badge/RoHub-FAIR_Executable_Research_Object-2ea44f?logo=Open+Access&logoColor=blue">
    </a>
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/13321552/222991560-185835b7-0801-41b1-9325-3015662995c4.png?raw=True" alt="thumbnail" width="300"/>
</p>

# How to run

## Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

## Running locally
You may also download the notebook from GitHub to run it locally:
1. Open your terminal

2. Check your conda install with `conda --version`. If you don't have conda, install it by following these instructions (see [here](https://docs.conda.io/en/latest/miniconda.html))

3. Clone the repository
    ```bash
    git clone https://github.com/eds-book-gallery/15d986da-2d7c-44fb-af71-700494485def.git
    ```

4. Move into the cloned repository
    ```bash
    cd 15d986da-2d7c-44fb-af71-700494485def
    ```

5. Create and activate your environment from the `.binder/environment.yml` file
    ```bash
    conda env create -f .binder/environment.yml
    conda activate 15d986da-2d7c-44fb-af71-700494485def
    ```  

6. Launch the jupyter interface of your preference, notebook, `jupyter notebook` or lab `jupyter lab`

# Credits
The **How to run** section was adapted from the [Project Pythia Cookbook](https://cookbooks.projectpythia.org/) project.
The workflow actions were adapted from [2i2c’s hub-user-image-template](https://github.com/2i2c-org/hub-user-image-template) released under BSD-3-Clause license.