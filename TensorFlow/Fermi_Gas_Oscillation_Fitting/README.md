# Fermi Gas Oscillation Fits
- Papers describing the 'non-hydrodynamic modes' that these fits were looking for include:
  - ### Jasmine Brewer, Paul Romatschke Phys.Rev.Lett. 115 (2015) no.19, 190404 (arXiv:1508.01199)
  - ### W. E. Lewis and P Romatschke 2017 New J. Phys. 19 023042 (open access)
  - ### W. E. Lewis (Thesis) Strongly Interacting Fermi Gases: Hydrodynamics and Beyond (arXiv:1804.10209)
  - ### H. Bantilan, J. T. Brewer, T. Ishii, W. E. Lewis, and P. Romatschke Phys. Rev. A 94, 033621 (arXiv:1605.00014)
- The data for this project is from: 
  - ### Enrico Vogt, Michael Feld, Bernd Fröhlich, Daniel Pertot, Marco Koschorreck, and Michael Köhl Phys. Rev. Lett. 108, 070404
    - Since I did not collect this data, I will not make it publicly available here.

- This project refactors some code originally written using other python libaries to tensorflow where I implement minibatch gradient descent with an adaptive learning (learning rate decreases as number of epochs increases) to find the maximum likelihood estimates for a set of model parameters. 

- The project also uses the observed Fisher information matrix to estimate the uncertainty in the MLE.  