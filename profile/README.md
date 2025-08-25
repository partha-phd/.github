## Parthasarathy Nadarajan's PhD Workspace 🎓

**Title:** Efficient Design of Vehicle Safety Systems based on Predicted Occupancy Grids and Statistical Learning

This organization contains the sources for the experimental framework included in the thesis and publications.

### Abstract

Recent advances in the sensing and computing technology have fuelled the research towards developing driverless vehicle technology. With human errors being the major cause of road accidents, autonomous or highly intelligent vehicles have the potential to positively impact tens of millions of people. One of the important but challenging problems for autonomous vehicles is to plan a safe, collision-free, trajectory. In order to achieve this, it is important not only to take into account the dynamic constraints of the vehicle, but also the motion of the traffic participants in the driving environment, such as cars, bicycles, and pedestrians. 

Therefore, it is crucial to reason about the motion behavior of the traffic participants in future time instances, so that the planned trajectory for the so called ego vehicle, the vehicle in which the safety algorithm operates, has a low risk of collision with the surrounding traffic participants. This work presents a model-based approach is presented to compute Predicted Occupancy Grid Maps (pOGMs), which are introduced as a grid-based probabilistic representation of the future traffic scenario that includes both behaviors of the traffic participants and interactions between them. However, due to the large number of possible trajectories for each traffic participant, the model-based approach incurs a high computational load, hindering its application in real-time vehicle safety systems. 

Thus, a machine learning approach has been adopted for computing pOGMs. A number of novel machine learning architectures based on random forests, denoising autoencoders, deconvolution networks, and convolutional variational autoencoders have been developed in this work. Additionally, a novel enriched representation of the current instance of a traffic scenario termed as the augmented Occupancy Grid Map (aOGM), has been introduced in this work to serve as the input for the machine learning algorithms. The developed algorithms have been using real-world data collected from three different road infrastructures: T-junctions, roundabouts, and highways. The applications of pOGMs in improving crucial vehicle safety components such as trajectory planning and criticality estimation have also been demonstrated. 

## Publications
The core publications related to this work are: 
- Parthasarathy Nadarajan and Michael Botsch. Probability estimation for predicted-occupancy grids in vehicle safety applications based on machine learning. *In 2016 IEEE Intelligent Vehicles Symposium (IV)*, pages 1285−1292. IEEE, 2016.
    - To cite this work in your research, please use:
      ```bibtex
      @inproceedings{nadarajan2016probability,
        author={Nadarajan, Parthasarathy and Botsch, Michael},
        booktitle={2016 IEEE Intelligent Vehicles Symposium (IV)},
        pages={1285--1292},
        year={2016},
        organization={IEEE}
      }
      ```
- Parthasarathy Nadarajan, Michael Botsch, and Sebastian Sardina. Predicted-occupancy grids for vehicle safety applications based on autoencoders and the random forest algorithm. *In 2017 International Joint Conference on Neural Networks (IJCNN)*, pages 1244−1251. IEEE, 2017.
    - To cite this work in your research, please use:
      ```bibtex
      @inproceedings{nadarajan2017predicted,
      title={Predicted-occupancy grids for vehicle safety applications based on autoencoders and the random forest algorithm},
      author={Nadarajan, Parthasarathy and Botsch, Michael and Sardina, Sebastian},
      booktitle={2017 International Joint Conference on Neural Networks (IJCNN)},
      pages={1244--1251},
      year={2017},
      organization={IEEE}
      }
      ```
- Parthasarathy Nadarajan, Michael Botsch, and Sebastian Sardina. Machine learning architectures for the estimation of predicted occupancy grids in road traffic. *Journal of Advances in Information Technology*, 9(1) : 1−9, 2018.
    - To cite this work in your research, please use:
      ```bibtex
      @article{nadarajan2018machine,
      title={Machine learning architectures for the estimation of predicted occupancy grids in road traffic},
      author={Nadarajan, Parthasarathy and Botsch, Michael and Sardina, Sebastian},
      journal={Journal of Advances in Information Technology},
      volume={9},
      number={1},
      pages={1--9},
      year={2018},
      publisher={Engineering and Technology Publishing}
      }
      ```
- Parthasarathy Nadarajan, Michael Botsch, and Sebastian Sardina. Continuous probabilistic motion prediction based on latent space interpolation. *In 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)*, pages 3796−3803. IEEE, 2023.
    - To cite this work in your research, please use:
      ```bibtex
      @inproceedings{nadarajan2023continuous,
      title={Continuous Probabilistic Motion Prediction Based on Latent Space Interpolation},
      author={Nadarajan, Parthasarathy and Botsch, Michael and Sardina, Sebastian},
      booktitle={2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC)},
      pages={3796--3803},
      year={2023},
      organization={IEEE}
      }
      ```
  
## Repositories
The source code to the algorithms developed during this work are provided in the following links: 
- Model Based Interaction-Aware Motion Prediction: [Repo link](https://github.com/partha-phd/motion-prediction-using-feature-learning.git).
- Machine Learning Based Interaction-Aware Motion Prediction: [Repo link](https://github.com/partha-phd/motion-prediction-using-feature-learning.git) and [Repo for Interpolation](https://github.com/partha-phd/motion-prediction-using-interpolation.git).
- Applications of pOGMs in Vehicle Safety (Trajectory Planning): [Repo link](https://github.com/partha-phd/trajectory-planning-using-RRT.git).
