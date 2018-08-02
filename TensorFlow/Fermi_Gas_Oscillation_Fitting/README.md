# Fermi Gas Oscillation Fits

- The data for this project is from: 
## Enrico Vogt, Michael Feld, Bernd Fröhlich, Daniel Pertot, Marco Koschorreck, and Michael Köhl Phys. Rev. Lett. 108, 070404
   - Since I did not collect this data, I will not make it publicly available here.

- This project refactors some code originally written using other python libaries to tensorflow where I implement minibatch gradient descent with an adaptive learning (learning rate decreases as number of epochs increases) to find the maximum likelihood estimates for a set of model parameters. 

- The project also uses the observed Fisher information matrix to estimate the uncertainty in the MLE.  