# Machine Learning - Neural network force-field training for ???

In this project you will work with a dataset of water molecules in a constant temperature molecular dynamics simulation. You will be provided with a dataset of 842 images that can be used for training the model, and an additional 200 images for validating the performance.

Prior work in the group has achieved neural network force fields with an accuracy of 5 meV/atom (energy) and 0.1 eV/A (forces) for the dataset provided. Your goal in this project is to improve this result by modifying the neural network architecture (number of layers/nodes, activiation function, etc.) and/or initialization and training procedure. It is recommended that you utilize the Simple-NN package, but you may also use any other software package, or implement/modify algorithms as needed.

the data is located in the `data` folder in the top level of this github repository named `water_data.traj` and `water_validation.traj`

## Midterm goal:

By the midterm you should be able to generate a neural network model with accuracy comparable to the accuracy already achieved in the group (see above).

### Midterm deliverables:

A zip file with the results including a log file with the RMSE values and input files.

## Final goal:

By the final you should have a neural network model and/or training strategy that has an improved accuracy for both energies and forces.

### Final deliverables:

A zip file with all model details as described in the midterm deliverable, along with a report explaining your strategy and the reasoning behind the improved performance.