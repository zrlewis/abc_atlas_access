# Allen Brain Cell Atlas - Data Access

The Allen Brain Cell Atlas (ABC Atlas) aims to empower researchers worldwide to
explore and analyze multiple whole-brain datasets simultaneously. As the Allen
Institute and its collaborators continue to add new modalities, species, and
insights to the ABC Atlas, this groundbreaking platform will keep growing,
opening up endless possibilities for groundbreaking discoveries and
breakthroughs in neuroscience. With the ABC Atlas, researchers everywhere can
gain new insights into the brain’s complex workings, advancing our
understanding of this amazing organ in ways we never thought possible.

## ABC Atlas Data Access JupyterBook Website
https://AllenInstitute.github.io/abc_atlas_access

## How to contribute 
[JupyterBook Contribution Guide](docs/jupyterbook/README.md)

Note: for scientific questions regarding the data this repository is accessing,
please use the
[Allen Institute's community forum](https://community.brain-map.org/).
If you are having an issue with the code or notebooks not running properly
please open an issue on this Github repository. However, please see below.

## Level of support
We are not currently supporting this code, but simply releasing it to the
community AS IS but are not able to provide any guarantees of support. The
community is welcome to submit issues, but you should not expect an active
response.

## Installation

To install base package with the cache object in your python environment, use
pip with the following command:

```console
pip install git+https://github.com/alleninstitute/abc_atlas_access.git
```

To install the package with all optional dependencies, specifically those needed
to re-run the notebooks, you can use the following command:

```console
pip install "abc_atlas_access[notebooks] @ git+https://github.com/alleninstitute/abc_atlas_access.git"
```

We assume that you already have Jupyter installed if you are re-running the
notebooks. Running the [getting_started notebook](https://alleninstitute.github.io/abc_atlas_access/notebooks/getting_started.html)
will also help you install the package.
