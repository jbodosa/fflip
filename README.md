## Notes

conda has trouble getting the right version of openmmtools if installed stepwise. So I had
to install the first couple of packages at once-
> conda create -n fflip3.7_test -c conda-forge -c omnia python=3.7 dask=2021.11.2 distributed=2021.11.2 dask-jobqueue=0.7.3  openmm=7.4.0 openmmtools=0.17.0

- I also made changes to the setup.py files in both rickflow and fflip
- Added rickflow to github
