# Convolutional-Variational-Autoencoder-QPC-Analysis

### Summary
This notebook builds an AI algorithm to map quantum transport characteristics to a latent space. The goal is to systematically judge whether a quantum device resembles Quantum Point Contact's ballistic quasi-1D transport characteristics or not. The algorithm is an autoencoder neural network written in Keras. 

### Funtionality
The autoencoder neural network is trained on 2,800 sets of simulated quantum transport data. Then 700 test data is mapped to the latent spce and visualized after t-SNE transformation. The two categories of data 'Ballistic' and 'Not-so-Ballistic' roughly occupies two separate areas in the latent space. The next step will be to try other loss functions that are more sensitive to the features instead of the exact pixel values of the data.

### Run locally
<ul>
 <li>Download Varitational Convolutional Autoencoder_QPC analysis.ipynb and the example data</li>
  <li>Update the directory to the data in the notebook</li>
  <li>Run the notebook</li>
  
  </ul>
