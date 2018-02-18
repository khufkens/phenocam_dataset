# PhenoCam V1.0 dataset - limited subset

This is a subset of the original PhenoCam Dataset V1 as described in Richardson et al. 2018. This dataset only includes high level products, and probably the most commonly used forms of data to be accessed by users.

Data included comprises of:

- data_record_4 (1 & 3-day time series as processed from ~half hourly images)
- data_record_5 (phenological transition dates extracted from 1 and 3-day time series)

For a full description of the dataset, including the rational and methodologies I refer to Richardson et al. 2018. The complete dataset can be [downloaded](https://daac.ornl.gov/cgi-bin/dsviewer.pl?ds_id=1511) from the Oak Ridgel National Laboratories Distributed Active Archive Center (ORNL DAAC, ~ 1.2 GB).

These data are visualized on the [explore.phenocam.io website](http://explore.phenocam.us) For selective, site based, data downloads I encourage people to use this interface.

## Download

To download the data clone the project using the following command in a terminal.

```bash
git clone https://github.com/khufkens/phenocam_dataset.git
```

or download a [zipped file](https://github.com/khufkens/phenocam_dataset/archive/master.zip) of the archive.

## References

Richardson, A.D., Hufkens, K., Milliman, T., Aubrecht, D.M., Chen, M., Gray, J.M., Johnston, M.R., Keenan, T.F., Klosterman, S.T., Kosmala, M., Melaas, E.K., Friedl, M.A., Frolking, S.  2018. Tracking vegetation phenology across diverse North American biomes using PhenoCam imagery. Scientific Data (in press).

Hufkens K., Basler J. D., Milliman T. Melaas E., Richardson A.D. 2018. [An integrated phenology modelling framework in R: Phenology modelling with phenor. Methods in Ecology & Evolution](http://onlinelibrary.wiley.com/doi/10.1111/2041-210X.12970/full), 9: 1-10.

## Acknowledgements

This project was is supported by the National Science Foundation’s Macro-system Biology Program (awards EF-1065029 and EF-1702697).
