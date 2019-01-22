# deep-traffic
MIT Challenge - Use Deep Reinforcement Learning to solve traffic

## Average Speed : 69.69 km/h

## Parameters
* lanesSide = 3;
* patchesAhead = 30;
* patchesBehind = 14;
This way we send almost the full map and we can look for long term rewards

* trainIterations = 300000;
Length of training

* var temporal_window = 0;

* Layers : 5 layers of 50-40-30-20-10 neurons

* TD parameters
    learning_rate: 0.001,
    momentum: 0.0,
    batch_size: 32,
    l2_decay: 0.01
    
    
* Experience Size : 5000

* Gamma : 0.9
