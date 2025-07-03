# MicStEv for Microstructure Evolution
![logo](https://raw.githubusercontent.com/fatihxuzun/MicStEv/main/MicStEv_logo.png)

## Dependencies
* MATLAB R2024b

## Installation
Download 'reference.p', 'reconstruct.p' and 'microstructure.p' to your project folder.

/myProjectFolder$

## exCaking Command Line
reference(grain_size_threshold, scale_resolution)

* grain_size_threshold - Treshold for minimum number of pixels a grain must contain (Default is 0)
* scale_resolution - Scaling factor for the image resolution, ranging from 0.0 to 1.0 (Default is 1.0)

reconstruct(random_seed, number_of_parallel_workers, termination_treshold, crossover_probability, mutation_probability, number_of_elite, mutation_range, mutation_range_expand, mutation_range_shrink, number_of_members)

* random_seed - Integer value used to initialize the random number generator for reproducibility (Default is 0)
* number_of_parallel_workers - Number of processes or threads to use for parallel computation (Default is 1)
* termination_treshold - Convergence criterion for stopping the algorithm (Default is 1e-3)
* crossover_probability - Probability that crossover will occur during reproduction (Default is 0.75)
* mutation_probability - Probability that a mutation will occur in an individual solution (Default is 0.05)
* number_of_elite - Number of elites that are preserved unchanged into the next generation (Default is 1)
* mutation_range - Initial pixelwise range within which gene values can mutate (Default is 0.2)
* mutation_range_expand - Factor by which the mutation range increases (Default is 1.1)
* mutation_range_shrink - Factor by which the mutation range decreases (Default is 0.99)
* number_of_members - Total number of individuals in each generation (Default is 9)

microstructure(grain_size_threshold, scale_resolution)

* grain_size_threshold - Treshold for minimum number of pixels a grain must contain (Default is 0)
* scale_resolution - Scaling factor for the image resolution, ranging from 0.0 to 1.0 (Default is 1.0)

## MicStEv Input Files
Follow the instructions from command window.

## Outputs
/myProjectFolder/dStore$

* data.mat
* microstructure.mat

## Scientific Usage
Please cite:

doi link to the paper
