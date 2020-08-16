# ShuTu

<img src="http://personal.psu.edu/dzj2/ShuTu/ShuTu_cell_char.jpg" width="100%"/>

Status: ShuTu CLI reconstruction code is working on Colab, as of 2019-10-12, with only a bit of work needed to get the Allen data into a format ShuTu likes (multi-page TIFF) 

ShuTu (Chinese for “dendrite”) is open source for neurite reconstruction. See the notebook, [ShuTu on Colab](https://colab.research.google.com/drive/1PQEWuFjUi3vo-1btNi6M5vXoNS3dTv5o#scrollTo=qQ5T40Rh0gJk), for how ShuTu can generate SWC files from brightfield image stacks. 

ShuTu demo datasets have been seen at around 2 GB. Smallest cell in the challenge dataset is ~6 GB; the average is ~20MB. Perhaps ShuTu on Colab can works for at least some cells. Larger might not work since ShuTu distributes work via MPI, but Colab only gives you one core so that doesn't scale on Colab. But MPI tools seem to be preinstalled on Colab so that's a good thing WRT using Colab as a free-tier demo of what would scale if more VM instances were in the MPI pool.

## ShuTu notebooks:
- ShuTu generating SWC for ShuTu demo data
  - [brightfield_neuron_swc_by_shutu.ipynb](https://colab.research.google.com/drive/1zdTS1HsAqdH5p4sk42TC6-uFM7f7XUdA#scrollTo=8aBV9zEcLJHm)
- ShuTu installing on Colab
  - [install_shutu_on_colab.ipynb](https://colab.research.google.com/drive/1wRnt5ceTs2Oau4g_BiYv09ZOLbv3cyWI#scrollTo=Q1eCY1mvHbCr) 
- ShuTu on Colab first test     
  - [first_manual_install_of_shutu_on_colab.ipynb](https://colab.research.google.com/drive/1PQEWuFjUi3vo-1btNi6M5vXoNS3dTv5o#scrollTo=qQ5T40Rh0gJk)
- **TBD:** ShuTu generating SWC for Allen data
  - [shutu_makes_swc_for_neuron_651806289.ipynb](https://colab.research.google.com/drive/1CczIvOKomTQexPznDIqb5wErnWJYlBTn#scrollTo=D0T393yXh-a_)
  - This is the main ShuTu notebook; the rest are earlier steps


## References
[ShuTu: Open-Source Software for Efficient and Accurate Reconstruction of Dendritic Morphology](https://www.frontiersin.org/articles/10.3389/fninf.2019.00068/full)
- Front. Neuroinform.
- 31 October 2019
- https://doi.org/10.3389/fninf.2019.00068

