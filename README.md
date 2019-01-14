# DS400Spring2019Planets

Selected Large Datafile are avaliable at https://psu.box.com/v/ds400spring2019planets

File descriptions:

- kplr_dr25_inj1_plti.txt is the first file you'll use.  It's in [IPAC format](https://irsa.ipac.caltech.edu/applications/DDGEN/Doc/ipac_tbl.html) which can be most easily read using 
the [astropy.io.ascii.read](http://docs.astropy.org/en/stable/io/ascii/)
For documentation of its contents, see https://exoplanetarchive.ipac.caltech.edu/docs/KSCI-19110-001.pdf

- kplr_dr25_gaia_fgk.csv: This file contains updated stellar properties for a subset of stars (those beleived to be best for planet hunting).  It may be advantageous to use stellar parameters from that file in place of those from the other files and/or to focus your attention on those star for model evaluation purposes.  

- DR25_DEModel_NoisyTargetList.txt: This file contains the KepID number of stars which have particularly challenge light curves.  It may be advantageous to exclude these stars for model evaluation purposes.

- Additional documentation and data files that may be of use are are avaliable from https://exoplanetarchive.ipac.caltech.edu/docs/KeplerSimulated.html.  In particular, astronomers have made use of the "Flux-level Transit Injection Products" for improving their models of the Kepler pipeline's detection efficiency.

- kplr_dr25_inj1_tces.txt contains information which may be useful for phase two of the project, but is not needed for phase one.

- kplr_dr25_inj1_robovetter_input.txt contains information which may be useful for phase two of the project, but is not needed for phase one.



