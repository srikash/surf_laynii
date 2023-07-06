# surf_laynii [![DOI](https://zenodo.org/badge/656805199.svg)](https://zenodo.org/badge/latestdoi/656805199)
Script that enables LAYNII layering using Freesurfer segmentations
You may need to run `chmod +x surf_laynii` to make it an executable.

### Example use

`surf_laynii -d /home/user/Data/Project-01/fs_recons -s sub-01`

#### Optional use cases
In case you want the rim files but want to run LAYNII with different parameters, or want to register the rim file to EPI space & only then running LAYNII, use the stop laynii flag '-l'. <br>
`surf_laynii -d /home/user/Data/Project-01/fs_recons -s sub-01 -l`

In case you want the rim files at a resolution higher/lower than the 0.3 mm default. <br>
`surf_laynii -d /home/user/Data/Project-01/fs_recons -s sub-01 -n 0.2`
