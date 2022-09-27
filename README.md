# CAROM Air

CAROM means "CARs On the Map tracked from the Air". It is our most recent work to track and localize vehicles using aerial videos taken by drones. It is designed for traffic scene reconstruction and analysis. See the following short [demo video](https://youtu.be/YQcnAQMWmas). Our research paper is currently under review.

[![CAROM Demo](https://img.youtube.com/vi/YQcnAQMWmas/0.jpg)](https://youtu.be/YQcnAQMWmas)

## Demo Videos

More detailed demo videos for qualitative evaluation are shown as follows.

* Tracking evaluation: [track 1a](https://youtu.be/9IsbQ_jfSlA), [track 1b](https://youtu.be/VWkGq62GtP8), [track 1c](https://youtu.be/LrPKceT6OoI), [track 1d](https://youtu.be/xesGTjivWwc).


# CAROM

CAROM means "CARs On the Map". It is a framework to track and localize vehicles using monocular traffic monitoring cameras on road infrastructures. The tracking results can be stored in files or in a database as records. Using the results, a traffic scene can be reconstructed and replayed on a map. See the following short [demo video](https://youtu.be/2OQ2Pf1BeHc), a [presentation](https://youtu.be/rbA0ppKy9Dc), and a preprint version of our [paper](https://arxiv.org/abs/2104.00893) on ICRA 2021 and a more detailed [paper](https://www.researchgate.net/profile/Jeffrey-Wishart/publication/350640893_Infrastructure-Based_Sensor_Data_Capture_Systems_for_Measurement_of_Operational_Safety_Assessment_OSA_Metrics/links/606b966c92851c91b1a6c16b/Infrastructure-Based-Sensor-Data-Capture-Systems-for-Measurement-of-Operational-Safety-Assessment-OSA-Metrics.pdf) on our work about the infrastructure.

[![CAROM Demo](https://img.youtube.com/vi/2OQ2Pf1BeHc/0.jpg)](https://youtu.be/2OQ2Pf1BeHc)

Through collaborating with the Maricopa County Department of Transportation (MCDOT) in Arizona, US, we constructed a small benchmarking dataset containing GPS data, infrastructure based camera videos, and drone videos to validate the vehicle tracking results. On average, the localization error is approximately 0.8 m and 1.7 m on average within the range of 50 m and 120 m from the cameras, respectively. 

## Demo Videos

More detailed demo videos for qualitative evaluation are shown as follows.

* [Demo videos at site 1A](https://youtu.be/pKGxqBnaGAk) (Eastbound of the intersection, ~10 minutes)
* [Demo videos at site 1B](https://youtu.be/79ZrOIpRCN0) (Northbound of the intersection, ~10 minutes)
* [Demo videos at site 1C](https://youtu.be/aFRLNki1Sq0) (Westbound of the intersection, ~10 minutes)
* [Demo videos at site 1D](https://youtu.be/pMOLFDCAGI4) (Southbound of the intersection, ~10 minutes)
* [Demo videos at site 2](https://youtu.be/cR5G8N1hxko) (East Osborn Road, ~10 minutes)
* [Validation with aerial videos at site 2](https://youtu.be/Z6AY0bTjV-4) (East Osborn Road)
* [Demo on four view fusion at site 1](https://youtu.be/eQwW7ZCzwtU) (Detailed slow motion)
* [Demo on speed estimation at site 1](https://youtu.be/8jOseFxUxsI) (Detailed slow motion)

## Publications

* Duo Lu, Varun C Jammula, Steven Como, Jeffrey Wishart, Yan Chen, Yezhou Yang, "**CAROM - Vehicle Localization and Traffic Scene Reconstruction from Monocular Cameras on Road Infrastructures**" *IEEE International Conference on Robotics and Automation (ICRA), 2021.*
* Niraj Altekar, Steven Como, Duo Lu, Jeffrey Wishart, Donald Bruyere, Faisal Saleem, K Larry Head, "**Infrastructure-Based Sensor Data Capture Systems for Measurement of Operational Safety Assessment (OSA) Metrics**" *SAE WCX Digital Summit, 2021.*
