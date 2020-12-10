# AV-Interactions-City-Traffic
Low-speed automated shuttles, from EasyMile and Navya, were tested respectively in Montréal, Canada and in Candiac, Canada, in mid and late 2019. Trajectories were extracted from video footage using [TrafficIntelligence](https://bitbucket.org/Nicolas/trafficintelligence).

<img src="imgs/tracking_ex_feature.png"/>

This repository provides samples of data from trajectories and interactions, captured from both test projects, that were used in a [submission for the 2021 TRB Annual Meeting]() and an [article under review for Accident Analysis and Prevention]().

## Installation
To get started clone this repository and install the required packages.

```sh
$ git clone https://github.com/FinestStone/AV-Interactions-City-Traffic.git
$ cd AV-Interactions-City-Traffic/
$ pip3 install -r requirements.txt
```

## Usage
* The database samples are provided in the [data folder](https://github.com/FinestStone/AV-Interactions-City-Traffic/tree/master/data).
* The [extraction folder](https://github.com/FinestStone/AV-Interactions-City-Traffic/tree/master/extraction) presents examples on extracting information of interest from trajectories and interactions and storing it in a CSV file.
* The [findings notebook](https://github.com/FinestStone/AV-Interactions-City-Traffic/blob/master/findings.ipynb) contains code used to produce the results.

## Credits
### Authors
* **Étienne Beauchamp** - *Initial work* - [FinestStone](https://github.com/FinestStone)
* **Nicolas Saunier** - *Coauthor and contributor* - [nsaunier](https://github.com/nsaunier)

See also the list of [contributors](https://github.com/FinestStone/AV-Interactions-City-Traffic/graphs/contributors) who participated in this project.

### Citations
To cite this work, please use the following article:

* É. Beauchamp, N. Saunier and M.-S. Cloutier. Study of Automated Shuttle Interactions in City Traffic Using Surrogate Measures ofSafety. In Transportation Research Board Annual Meeting, 2021