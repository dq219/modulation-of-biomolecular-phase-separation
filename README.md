# modulation-of-biomolecular-phase-separation

This repository contains data and analysis scripts for the dominance and tie line analysis described in the manuscript [Molecular mechanisms of condensate modulation from energy dominance analysis](https://www.biorxiv.org/content/10.1101/2023.11.02.565376v3). The folders describe:

- [G3BP1/RNA/suramin system](./G3BP1-RNA-suramin)
	- [PhaseScan data](./G3BP1-RNA-suramin/PhaseScan), comprising around 60,000 microfluidic droplet samples at a range of total G3BP1, RNA, and suramin concentrations. The .ipynb script analyses the data and produces all figures shown in the manuscript.
	- [Diffusional sizing data](./G3BP1-RNA-suramin/sizing), comprising the hydrodynamic radius measurement of G3BP1 as a function of total RNA concentration, with and without suramin in the samples. The .ipynb script plots the data and carries out a basic binding function fitting.
	
- [Collection of literature data](./collection), where dominance values are extracted from either homotypic or heterotypic responses. The .ipynb script is used to produce table in the manuscript.

Get in touch with dq219@cam.ac.uk or 000.gdz@gmail.com for any questions. Thanks for your interest! :)

## Dependencies
Libraries used:
- `numpy`
- `scipy`
- `matplotlib`
- `pandas`

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

