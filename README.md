# Ship Routing Algorithms for Just-In-Time and Energy Efficient Voyages – Comparing Simple and Advanced Implementations of a Genetic Algorithm

Rising fuel costs, the ever-increasing number of regulations and their tightening demonstrates the need to minimize fuel consumption in container shipping. With the development of an interactive Jupyter notebook, we want to meet this need. The developed script is intended to assist in planning fuel-saving routes and takes into account the engine power of the vessel, the condition of the weather and the sea, and also possible just-in-time deadlines. 

For this purpose, the engine power is first modeled in order to be able to make statements about which speed is possible under which weather conditions. By using a genetic algorithm, a multi-objective optimization is then performed, aiming at the lowest possible fuel consumption while at the same time meeting the scheduled deadlines. Thereby the algorithm is tested in two different specifications. One with a constant and over the route not changeable engine power and the other with a changeable engine power. With the first specification, a temporal window can only be considered up to a certain degree due to the constant engine power. The second specification with the variable engine power, however, should allow the calculation of just-in-time routes. In order to be able to make statements about the two specifications, they are compared concerning applicability, constraints and performance. 

You can find the both different specifications of the algorithm in the main path of this repository, or also in the Google Colab environment ([simple algorithm](https://drive.google.com/file/d/1QrRJWd1SI-4rbmLsx19NNWkL_KpcW-HI/view?usp=sharing), [advanced algorithm](https://drive.google.com/file/d/1Z9NRGjNQhzFDFrzukAmwxJOnZCo1QtSM/view?usp=sharing)). The two scripts can be run there interactively, or are downloadable as part of the repository to run locally. 
In addition to these scripts, there are some more files in the repository, which are the basis for the algorithm, and some more notebooks for preparation. 

This software was developed as part of the study project "Copernicus Marine Services for Energy optimized Cargo Ship routing" in the summerterm 2021 at ifgi at the University of Münster.
