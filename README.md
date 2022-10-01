# CAROM Air

CAROM Air means "CARs On the Map tracked from the Air". It is our recent work to track and localize vehicles using aerial videos taken by drones. It is designed for traffic scene reconstruction and analysis. See the following short [demo video](https://youtu.be/YQcnAQMWmas). Our research paper is currently under review.

[![CAROM Demo](https://img.youtube.com/vi/YQcnAQMWmas/0.jpg)](https://youtu.be/YQcnAQMWmas)

## Demo Videos

More detailed demo videos for qualitative evaluation are shown as follows.

* Keypoints and masks
  * [Track 0a](https://youtu.be/jSyA9yeg9CE) (Roundabout in Mesa, AZ, ~25 minutes)
  * [Track 0b](https://youtu.be/9kRBCou6yco) (Intersection in Mesa, AZ, ~25 minutes)
* Tracking evaluation
  * [Track 1a](https://youtu.be/9IsbQ_jfSlA) (Roundabout in Mesa, AZ, ~16 minutes)
  * [Track 1b](https://youtu.be/VWkGq62GtP8) (Intersection in Salt River Community, AZ, ~25 minutes)
  * [Track 1c](https://youtu.be/LrPKceT6OoI) (Local road segment in Tempe, AZ, ~23 minutes)
  * [Track 1d](https://youtu.be/xesGTjivWwc) (Highway segment in Salt River Community, AZ, ~24 minutes)
* Model fitting evaluation
  * [Track 2a](https://youtu.be/9N8S6Fr_HoQ) (Hatchback, first flight)
  * [Track 2b](https://youtu.be/wqA7cpWiRuc) (Hatchback, second flight)
  * [Track 2c](https://youtu.be/C7GBcROezGk) (SUV, first flight)
  * [Track 2d](https://youtu.be/5pk7EKnmlNA) (SUV, second flight)
  * [Track 2e](https://youtu.be/8HtYUmEzJ8s) (Sedan, first flight)
  * [Track 2f](https://youtu.be/xJDAWIf3Zec) (Sedan, second flight)
* Localization evaluation
  * [Track 3a](https://youtu.be/ts7h4i6Cz4w) (Vehicle A, seven passes: 0:09, 3:08, 4:50, 5:58, 7:39, 10:34, 14:14)
  * [Track 3b](https://youtu.be/CXOICJtjKJE) (Vehicle A, eight passes: 0:00, 2:30, 3:36, 5:01, 6:41, 11:04, 12:08, 13:34)
  * [Track 3c](https://youtu.be/5baGciKmBu0) (Vehicle A, five passes: 0:12, 5:14, 8:56, 10:00, 12:00)
  * [Track 3d](https://youtu.be/e8xckoBgYyQ) (Vehicle A, four passes: 0:00, 1:30, 4:30, 5:32)
  * [track 3e](https://youtu.be/K6Eu_fKIa7A) (Vehicle B, four passes: 1:34, 6:14, 10:12, 12:35)
  * [track 3f](https://youtu.be/dzXh-6few7g) (Vehicle B, three passes: 0:53, 4:10, 6:22)
  * [track 3g](https://youtu.be/E0oVavZ-r_g) (Vehicle B, six passes: 1:49, 4:54, 8:17, 10:56, 15:01, 17:30)
  * [track 3h](https://youtu.be/KM2lxBYVKlY) (Vehicle B, seven passes: 2:28, 3:50, 7:38, 8:41, 12:47, 14:19, 17:13)
  * [track 3i](https://youtu.be/wc5e3D2WT0w) (Vehicle B, four passes: 0:28, 4:14, 6:29, 8:47)
* Dataset demo
  * [Roundabouts](https://youtu.be/4hF1ABO0-24)
  * [Intersections](https://youtu.be/4Drjxmoe4Sc)
  * [Local road segments](https://youtu.be/BPsEchi_qWU)
  * [Highway segments](https://youtu.be/R5io_pBuvpM)


# CAROM

CAROM means "CARs On the Map". It is a framework to track and localize vehicles using monocular traffic monitoring cameras on road infrastructures. The tracking results can be stored in files or in a database as records. Using the results, a traffic scene can be reconstructed and replayed on a map. See the following short [demo video](https://youtu.be/2OQ2Pf1BeHc), a [presentation](https://youtu.be/rbA0ppKy9Dc), and a preprint version of our [paper](https://arxiv.org/abs/2104.00893) on ICRA 2021 and a more detailed [paper](https://www.researchgate.net/profile/Jeffrey-Wishart/publication/350640893_Infrastructure-Based_Sensor_Data_Capture_Systems_for_Measurement_of_Operational_Safety_Assessment_OSA_Metrics/links/606b966c92851c91b1a6c16b/Infrastructure-Based-Sensor-Data-Capture-Systems-for-Measurement-of-Operational-Safety-Assessment-OSA-Metrics.pdf) on our work about the infrastructure.

[![CAROM Demo](https://img.youtube.com/vi/2OQ2Pf1BeHc/0.jpg)](https://youtu.be/2OQ2Pf1BeHc)

Through collaborating with the Maricopa County Department of Transportation (MCDOT) in Arizona, US, we constructed a small benchmarking dataset containing GPS data, infrastructure based camera videos, and drone videos to validate the vehicle tracking results. On average, the localization error is approximately 0.8 m and 1.7 m on average within the range of 50 m and 120 m from the cameras, respectively. 

## Demo Videos

More detailed demo videos for qualitative evaluation are shown as follows.

* [Demo videos at site 1A](https://youtu.be/pKGxqBnaGAk) (Eastbound of the intersection, Anthem, AZ, ~10 minutes)
* [Demo videos at site 1B](https://youtu.be/79ZrOIpRCN0) (Northbound of the intersection, Anthem, AZ, ~10 minutes)
* [Demo videos at site 1C](https://youtu.be/aFRLNki1Sq0) (Westbound of the intersection, Anthem, AZ, ~10 minutes)
* [Demo videos at site 1D](https://youtu.be/pMOLFDCAGI4) (Southbound of the intersection, Anthem, AZ, ~10 minutes)
* [Demo videos at site 2](https://youtu.be/cR5G8N1hxko) (East Osborn Road, Scottsdale, AZ, ~10 minutes)
* [Validation with aerial videos at site 2](https://youtu.be/Z6AY0bTjV-4) (East Osborn Road, Scottsdale, AZ)
* [Demo on four view fusion at site 1](https://youtu.be/eQwW7ZCzwtU) (Detailed slow motion, Anthem, AZ)
* [Demo on speed estimation at site 1](https://youtu.be/8jOseFxUxsI) (Detailed slow motion, Anthem, AZ)

## Publications

* Duo Lu, Varun C Jammula, Steven Como, Jeffrey Wishart, Yan Chen, Yezhou Yang, "**CAROM - Vehicle Localization and Traffic Scene Reconstruction from Monocular Cameras on Road Infrastructures**", *IEEE International Conference on Robotics and Automation (ICRA), 2021.*
* Niraj Altekar, Steven Como, Duo Lu, Jeffrey Wishart, Donald Bruyere, Faisal Saleem, K Larry Head, "**Infrastructure-Based Sensor Data Capture Systems for Measurement of Operational Safety Assessment (OSA) Metrics**", *SAE WCX Digital Summit, 2021.*
* Anshuman Srinivasan, Yoga Mahartayasa, Varun Chandra Jammula, Duo Lu, Steven Como, Jeffrey Wishart, Maria Elli, Yezhou Yang, Hongbin Yu, "**Infrastructure-based LiDAR Monitoring for Assessing Automated Driving Safety**", *SAE WCX Digital Summit, 2022.*.
