# Datasets for Inverse Reinforcement Learning / Dynamic Discrete Choice Models

A curated list of open datasets capturing agent movements and choices through geographical spaces or economic decisions, suitable for inverse reinforcement learning projects.

## Discrete Economic Choices

- **[Career Decisions of Young Men](https://github.com/lindamaok899/student-project-lindamaok899)**: Utilized by Keane and Wolpin (1997), this dataset tracks the educational and occupational choices of young men over time, providing insights into career path decisions.

- **[Bus Engine Replacement Data](https://www.kaggle.com/datasets/erichschulman/bus1234.csv)**: Analyzed in John Rust's seminal 1987 paper, this dataset details the maintenance decisions of a bus company regarding engine replacements.
  
- **[The Discrete Choice Data Bank](https://github.com/alvarogutyerrez/TheDiscreteChoiceDataBank?utm_source=chatgpt.com)**  
  A curated collection of publicly available discrete choice datasets across various fields, including transport, health economics, and consumer behavior. This resource is invaluable for modeling dynamic decision-making processes.

## Vehicle Trajectories

- **[HighD Dataset](https://levelxdata.com/highd-dataset/)** and **[inD Dataset](https://levelxdata.com/ind-dataset/)**: HighD and inD datasets, collected using drones over German highways and intersections, respectively, provide high-precision vehicle trajectory data. HighD focuses on highway traffic with detailed information on vehicle positions, speeds, and maneuvers, while inD captures urban intersections, emphasizing pedestrian and cyclist interactions. These datasets are invaluable for traffic behavior analysis and autonomous driving research.

- **[NGSIM Vehicle Trajectory Data (US-101)](https://www.kaggle.com/datasets/nigelwilliams/ngsim-vehicle-trajectory-data-us-101?select=trajectories-0750am-0805am.txt)**: Part of the NGSIM initiative, this dataset includes detailed vehicle trajectory data captured on the US-101 freeway in California. It is valuable for studying traffic flow, lane-changing behavior, and vehicle interactions.

- **[100-Driver Naturalistic Driving Dataset](https://100-driver.github.io/)**: A naturalistic driving dataset capturing real-world trajectories from 100 drivers. It provides detailed data on driving behavior, useful for studying driver attention, vehicle control, and safety interventions.

- **[Round Dataset](https://levelxdata.com/round-dataset/)**: Collected using drones over roundabouts in Germany, this dataset focuses on vehicle trajectories in complex traffic situations, emphasizing interactions at roundabouts and supporting research on autonomous navigation.

- **[PishguVe Dataset](https://github.com/TeCSAR-UNCC/PishguVe)**: A detailed vehicle trajectory dataset from PishguVe, offering data on driving behaviors such as lane changes, acceleration, and braking in diverse traffic conditions. Useful for machine learning applications in autonomous driving systems.

- **[T-Driver Dataset](https://www.kaggle.com/datasets/arashnic/tdriver)**: A rich dataset of GPS and vehicle trajectory data collected from taxi drivers. This dataset is designed to study driving styles, safety, and operational efficiency in urban areas.

- **[COMPASS Connected Car Vehicle Trajectories and Behaviours Dataset](https://data.cdrc.ac.uk/dataset/compass-connected-car-vehicle-trajectories-and-behaviours)**: This dataset includes connected car trajectory data with detailed behavioral patterns, offering insights into vehicle interactions and driving behaviors in diverse scenarios.

- **[Ithaca365](https://ithaca365.mae.cornell.edu/c)**  
  A comprehensive dataset collected along a 15 km route under diverse scenes (urban, highway, rural, campus), weather conditions (snow, rain, sun), times (day/night), and traffic conditions. It includes images and point clouds from cameras and LiDAR sensors, with high-precision GPS/INS data, supporting research on perception under challenging weather conditions.

- **[Mobile Century Experiment GPS Trajectory Data](https://github.com/ucbtrans/mcdata)**: Contains 8 hours of GPS data from 100 vehicles on a 10-mile stretch of I-880 in California, collected during the Mobile Century experiment by UC Berkeley.

- **[Taxi Trajectory Dataset](https://www.kaggle.com/datasets/crailtap/taxi-trajectory/data)**: Contains GPS trajectory data from taxi trips, providing insights into urban mobility patterns. This dataset is useful for research on route optimization, traffic prediction, and urban transportation planning.

## Human Trajectories

- **[OpenTraj](https://github.com/crowdbotp/OpenTraj)**: A human trajectory prediction dataset benchmark that introduces existing datasets for human trajectory prediction tasks. It provides tools to load, visualize, and analyze datasets, supporting multiple datasets for comprehensive analysis.

- **[trajdata](https://github.com/NVlabs/trajdata)**: A unified interface to multiple human trajectory datasets, simplifying access and analysis across various sources. It provides a simple, uniform, and efficient representation and API for trajectory and map data, facilitating research in trajectory forecasting.

- **[GeoLife GPS Trajectory Dataset](https://www.microsoft.com/en-us/research/publication/geolife-gps-trajectory-dataset-user-guide/)**: Collected by Microsoft Research Asia, this dataset includes 17,621 trajectories from 182 users over three years, detailing movements such as walking, cycling, and driving.

- **[GPS Trajectories with Transportation Mode Labels](https://www.microsoft.com/en-us/research/publication/gps-trajectories-with-transportation-mode-labels/)**: This dataset provides GPS trajectories labeled with transportation modes like walking, biking, and driving, useful for analyzing movement patterns.

## Virtual Movements

- **[AI4Animation](https://github.com/sebastianstarke/AI4Animation)**: A collection of motion datasets and tools for character animation, useful for analyzing avatar movements in virtual environments.

## Gaming Datasets

- **[Basketball-U, Football-U, and Soccer-U Datasets](https://arxiv.org/html/2405.17680)**: These datasets provide trajectory sequences with xy-coordinates (in yards) for players in basketball, football, and soccer games, respectively. Each dataset includes 91 games, offering unnormalized coordinates and insights into player movements.

- **[Counter-Strike: Global Offensive (CS:GO) Agent Data](https://cs230.stanford.edu/projects_fall_2021/reports/102988723.pdf)**: This dataset captures the gameplay data of an AI agent playing CS:GO, including enemy detection via a YOLOv5 network and movement control through a deep neural network, enabling research on real-time decision-making in FPS games.

- **[StarCraftImage Dataset](https://arxiv.org/abs/2401.04290)**: Compiled from StarCraft II replays, this dataset contains 3.6 million images summarizing gameplay, with formats like RGB and grayscale. It supports analysis of complex multi-agent behaviors in strategy games.

- **[Awesome Game Datasets](https://github.com/leomaurodesenv/game-datasets)**: A curated list of datasets related to game development, including player and avatar movement data.

## Other

- **[TrajAir](https://theairlab.org/trajair/)**: A general aviation trajectory dataset capturing aircraft operations around non-towered airports. It includes recorded trajectories of multiple aircraft along with corresponding weather conditions, useful for training, testing, and benchmarking algorithms related to trajectory prediction, including socially-aware models.
