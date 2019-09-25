# DeepDownscaling
## Deep learning approaches for climate downscaling by the Santander Met Group

Downscaling is a methodology widely used to bridge the gap between the coarse resolution of Global Climate Models (GCMs) and the local scale. In this decade, deep learning has recently landed in the downscaling scene ([Vandal,2017](http://delivery.acm.org/10.1145/3100000/3098004/p1663-vandal.pdf?ip=193.144.210.92&id=3098004&acc=ACTIVE%20SERVICE&key=DD1EC5BCF38B3699%2E7E2EC88036375C9D%2E4D4702B0C3E38B35%2E4D4702B0C3E38B35&__acm__=1568215237_3e6de1805cae418d3adc967d411aeb3a)),([Rodrigues,2018](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8588749)) showing promising results to reproduce the local variability of climate variables. In particular, convolutional neural networks ([LeCun,1995](https://www.researchgate.net/profile/Yann_Lecun/publication/2453996_Convolutional_Networks_for_Images_Speech_and_Time-Series/links/0deec519dfa2325502000000.pdf)) stood out over benchmark methods in the largest-to-date downscaling intercomparison study ([author,year]), which is framed under the european cost-action VALUE ([Gutiérrez,2018](https://rmets.onlinelibrary.wiley.com/doi/epdf/10.1002/joc.5462)). In order to provide the impact and mitigation communities with reliable high-resoluted climate change projections, it is especially relevant to evaluate how downscaling tools would perform under these scenarios, where extrapolation capabilities are expected. A simple analysis involving the extrapolation abilities of deep learning ended up with succesfull results for both downscaling of precipitation and temperature ([author,year]). However, a more detailed analysis regarding the performance of downscaling methods (including deep learning) under the framework of the VALUE intercomparison project was carried out ([author,year]), suggesting that convolutional models maintain stable while working on future climate conditions.

The concern about transparency and reproducibility keeps growing due to its importance to develop top quality science. Therefore, the main objective of this repository is to maintain the companion notebooks (and other documents) related to the applications of deep learning in downscaling presented in several journal papers by the [Santander Met Group](http://www.meteo.unican.es/en/view/publications). The code shared shows how to go through all the steps of the entire process: loading and post-processing the data, perform the downscaling, validating the results obtained and visualizing them. For most of these tasks, we rely on [climate4R](http://www.meteo.unican.es/climate4R), a bundle of `R` packages developed by the Santander Met Group for transparent climate data access, post processing (including bias correction and downscaling) and visualization. A more detailed and comprehensive description of the main climate4R packages (loadeR, transformeR, downscaleR, visualizeR and climate4R.value) can be found in the [climate4R repository](https://github.com/SantanderMetGroup/notebooks), which contains a battery of notebooks with worked examples. Besides, we also use the [`keras`](https://cran.r-project.org/web/packages/keras/index.html) library, which provides an `R` interface to [Keras](https://keras.io), a high-level neural networks API which supports arbitrary network architectures and is seamlessly integrated with [TensorFlow](https://www.tensorflow.org/) (note that Keras and TensorFlow are the state of the art in deep learning tools).

The table below resumes the notebooks contained in this respository along with information of the respective published (or on going) journal articles.
 
| notebook  | Article Title | Journal | DOI  	
|---|---|---|---
| 2019_deepDownscaling_GMD_CNN (.ipynb)                    2019_deepDownscaling_GMD_FULL (.pdf, .Rmd)| Configuration and Intercomparison of Deep Learning Neural Models for Statistical Downscaling | Geoscientific Model Development |
|  |  |  |
