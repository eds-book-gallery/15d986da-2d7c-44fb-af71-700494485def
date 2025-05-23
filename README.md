# Tree crown detection using DeepForest

<p align="center">
    <a href="https://github.com/eds-book/15d986da-2d7c-44fb-af71-700494485def/actions/workflows/monthly-build.yaml/badge.svg">
        <img alt="Continuous integration badge" src="https://github.com/eds-book/15d986da-2d7c-44fb-af71-700494485def/actions/workflows/monthly-build.yaml/badge.svg">
    </a>
    <a href="http://mybinder.org/v2/gh/eds-book/15d986da-2d7c-44fb-af71-700494485def/main?labpath=notebook.ipynb">
        <img alt="Binder" src="https://mybinder.org/badge_logo.svg">
    </a>
    <a href="https://doi.org/10.5281/zenodo.8309661">
        <img alt="doi" src="https://zenodo.org/badge/493442887.svg">
    </a>
    <a href="https://github.com/alan-turing-institute/environmental-ds-book/pull/5">
        <img alt="notebook review" src="https://img.shields.io/badge/view-review-purple">
    </a>
</p>

<p align="center">
<img src="images/thumbnail.png" alt="thumbnail" width="500"/>
</p>

## How to run

### Running on Binder
The notebook is designed to be launched from Binder. 

Click the **Launch Binder** button at the top level of the repository

### Running locally
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