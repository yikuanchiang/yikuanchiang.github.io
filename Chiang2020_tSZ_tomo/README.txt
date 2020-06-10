This dataset is released together with Chiang et al., 2020, arXiv:20XX.XXXXXXX
"The Cosmic Thermal History Probed by Sunyaev-Zeldovich Effect Tomography"

The package contains three sets of products:

1. The tomographic cosmic Sunyaev-Zeldovich background measurements in Table 2 of the paper

2. The masks used in the paper
	- healpix n_side=2048, ring-ordered
	- TRUE for unmasked

3. CMB subtracted Planck HFI maps
	- Original Planck maps are bandpass corrected light maps from Planck Collaboration 2016, A&A, 594, A8
	- CMB subtraction is done over 100 to 353 GHz using the CMB map from Bobin, Sureau, & Starck 2016, A&A, 591, A50
	- healpix n_side=2048, ring-ordered
	- unit: MJy/sr, with the IRAS convention assuming an in-band spectrum of nu I_nu = constant