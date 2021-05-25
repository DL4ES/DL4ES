# The DL4ES book

>"Deep learning for the Earth Sciences -- A comprehensive approach to remote sensing, climate science and geosciences"<br>
>Editors: Gustau Camps-Valls, Devis Tuia, Xiao Xiang Zhu, Markus Reichstein<br>
>Publisher: Wiley & Sons, inc., 2021<br>

![alt text](https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1617079458l/57573449.jpg)

## Cite it

> @Book{CampsValls21wiley,<br>
> Title = {Deep learning for the Earth Sciences: A comprehensive approach to remote sensing, climate science and geosciences},<br>
> Author = {Camps-Valls, G. and Tuia, D. and Zhu, X.X. and Reichstein, M.},<br>
> Publisher = {Wiley \& Sons},<br>
> isbn = {978-1-119-64614-3},<br>
> Year = {2021},<br>
> }<br>

## Preview it

https://books.google.es/books?id=5P5DzgEACAAJ&dq=%22Deep+learning+for+the+Earth+Sciences%22&hl=en&sa=X&ved=2ahUKEwimm8GygYXwAhW4BGMBHWpJDf8Q6AEwAHoECAIQAg

## Buy it

https://www.amazon.com/Deep-learning-Earth-Sciences-comprehensive/dp/1119646146/

# Links to toolboxes, code and data

#### **Chapter 01: Introduction**

Some review papers of interest:
* Remote sensing
	- X. X. Zhu et al., "Deep Learning in Remote Sensing: A Comprehensive Review and List of Resources," in IEEE Geoscience and Remote Sensing Magazine, vol. 5, no. 4, pp. 8-36, Dec. 2017, doi: 10.1109/MGRS.2017.2762307. https://ieeexplore.ieee.org/abstract/document/8113128
	- L. Zhang, L. Zhang and B. Du, "Deep Learning for Remote Sensing Data: A Technical Tutorial on the State of the Art," in IEEE Geoscience and Remote Sensing Magazine, vol. 4, no. 2, pp. 22-40, June 2016, doi: 10.1109/MGRS.2016.2540798. https://ieeexplore.ieee.org/abstract/document/7486259
	- Ma, Lei, et al. "Deep learning in remote sensing applications: A meta-analysis and review." ISPRS journal of photogrammetry and remote sensing 152 (2019): 166-177. https://www.sciencedirect.com/science/article/pii/S0924271619301108
	- Yuan, Qiangqiang, et al. "Deep learning in environmental remote sensing: Achievements and challenges." Remote Sensing of Environment 241 (2020): 111716. https://www.sciencedirect.com/science/article/pii/S0034425720300857
* Geoscience
	-Reichstein, M., Camps-Valls, G., Stevens, B., Jung, M., Denzler, J., & Carvalhais, N. (2019). Deep learning and process understanding for data-driven Earth system science. Nature, 566(7743), 195-204. https://www.nature.com/articles/s41586-019-0912-1.
	- Bergen, Karianne J., et al. "Machine learning for data-driven discovery in solid Earth geoscience." Science 363.6433 (2019). https://science.sciencemag.org/content/363/6433/eaau0323.abstract
* Climate science
	- Rasp, Stephan, Michael S. Pritchard, and Pierre Gentine. "Deep learning to represent subgrid processes in climate models." Proceedings of the National Academy of Sciences 115.39 (2018): 9684-9689. https://www.pnas.org/content/115/39/9684.short
	- Jones, Nicola. "How machine learning could help to improve climate forecasts." Nature News 548.7668 (2017): 379. https://www.nature.com/articles/548379a
	- Dueben, Peter D., and Peter Bauer. "Challenges and design choices for global weather and climate models based on machine learning." Geoscientific Model Development 11.10 (2018): 3999-4009. https://gmd.copernicus.org/articles/11/3999/2018/

#### **Chapter 02: Learning Unsupervised Feature Representations of Remote Sensing Data with Sparse Convolutional Networks**

#### **Chapter 03: Generative Adversarial Networks in the Geosciences**

#### **Chapter 04: Deep Self-taught Learning in Remote Sensing**

#### **Chapter 05: Deep Learning-based Semantic Segmentation in Remote Sensing**

#### **Chapter 06: Object Detection in Remote Sensing**

#### **Chapter 07: Deep Domain adaptation in Earth Observation**

#### **Chapter 08: Recurrent Neural Networks and the Temporal Component**

#### **Chapter 09: Deep Learning for Image Matching and Co-registration**

#### **Chapter 10: Multisource Remote Sensing Image Fusion**

#### **Chapter 11: Deep Learning for Image Search and Retrieval in Large Remote Sensing Archives**

* https://git.tu-berlin.de/rsim

#### **Chapter 12: Deep Learning for Detecting Extreme Weather Patterns**

#### **Chapter 13: Spatio-temporal Autoencoders in Weather and Climate Research**

#### **Chapter 14: Deep Learning to Improve Weather Predictions**

#### **Chapter 15: Deep Learning and the Weather Forecasting Problem: Precipitation Nowcasting**

#### **Chapter 16: Deep Learning for High-dimensional Parameter Retrieval**

#### **Chapter 17: A review of Deep Learning for cryospheric studies**

Here are the major data centers, repositories, and providers for cryospheric studies:
* US National Snow and Ice Data Center (https://nsidc.org)
* US National Science Foundation Arctic Data Center (https://arcticdata.io)
* US Antarctic Program Data Center (http://www.usap-dc.org})
* European Space Agency Climate Change Initiative (http://cci.esa.int)
	- Antarctic Ice Sheet  (http://esa-icesheets-antarctica-cci.org)
	- Greenland Ice Sheet  (http://esa-icesheets-greenland-cci.org)
	- Glaciers (http://www.esa-glaciers-cci.org)
	- Permafrost (http://cci.esa.int/Permafrost)
	- Sea ice (http://cci.esa.int/seaice)
	- Snow (http://cci.esa.int/node/274/)
* Canadian Cryospheric Information Network (https://www.ccin.ca)
* China National Tibetan Plateau Data Center (https://data.tpdc.ac.cn/en/)
	
Below we list the data and codes published in the cryospheric studies reviewed in this chapter, grouped by the cryospheric components.
* Glaciers
	- Detection of glacier calving margins with convolutional neural networks \citep{mohajerani2019}
	Code and data: https://github.com/yaramohajerani/FrontLearning
	- Automatically delineating the calving front of Jakobshavn Isbr{\ae} from multitemporal TerraSAR-X images \citep{zhang2019}
	Training and test data: https://doi.org/10.1594/PANGAEA.897066
	- ALpine Parameterized Glacier Model (ALPGM) \citep{bolibar2020}
	Code and sample data: https://github.com/JordiBolibar/ALPGM
	
* Ice sheet
	- DeepBedMap: Antarctica Ice Sheet bed elevation using a super resolution deep neural network \citep{leong2020}
	Code: https://github.com/weiji14/deepbedmap
	Training experiments: https://www.comet.ml/weiji14/deepbedmap
	Digital bed elevation model: https://doi.org/10.17605/OSF.IO/96APW
	
* Snow
	- Estimating snow depth on Arctic sea ice using satellite microwave radiometry and a neural network \citep{Braakmann-Folgmann2019}
	Sample code and data: https://github.com/AnneBF/snownet
	
* Permafrost
	- Automatic mapping of thermokarst landforms from remote sensing images using deep learning \citep{huang2018}
	Code: https://github.com/yghlc/DeeplabforRS
	
	- Using deep learning to map retrogressive thaw slumps from CubeSat images  \citep{huang2020}
	Code: https://github.com/yghlc/Landuse\_DL
	Training and test data: https://doi.pangaea.de/10.1594/PANGAEA.908909
        - High-resolution mapping of spatial heterogeneity in ice wedge polygon geomorphology near Prudhoe Bay, Alaska \citep{abolt2020}
	Code and data: https://doi.org/10.1594/PANGAEA.910178

* River ice
	- River ice segmentation with deep learning \citep{singh2019}
	Code: https://github.com/abhineet123/river\_ice\_segmentation
	Data: https://ieee-dataport.org/open-access/alberta-river-ice-segmentation-dataset

#### **Chapter 18: Emulating Ecological Memory with Recurrent Neural Networks**

#### **Chapter 19: Applications of Deep Learning in Hydrology**

#### **Chapter 20: Deep Learning of Unresolved Turbulent Ocean Processes in Climate Models**

#### **Chapter 21: Deep Learning for the Parametrization of Subgrid Processes in Climate Models**

#### **Chapter 22: Using Deep Learning to Correct Theoretically-Derived Models**

* https://github.com/PAGWatson/Lorenz96_and_neural_networks

#### **Chapter 23: Outlook**




