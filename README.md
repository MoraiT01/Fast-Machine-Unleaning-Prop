# Fast Machine Unlearning Proposal

This repository adds more to the Repository of https://github.com/vikram2000b/Fast-Machine-Unlearning and originates from a branch of the named repository.

## Goal

The experiments conducted in this repository aimed to test if a noise generator shows better performance than a noise batch in the frame work of the unlearning algorithm discussed in the [FEMU Paper](https://ieeexplore.ieee.org/abstract/document/10113700?casa_token=TvcLIE5EM04AAAAA:oO91nE4YNSVD4AG5D3-haF4biywQv-VQt8IiKPPVk1jJIS4vNrz3afIxWjl0cIgH9r8rz99TtLSTtQ)

## Usage

`MachineUnlearning.ipynb`: Does exist in the original repo too. Changed to offer more usability, especially the automatic saving of the model at the end of the 

`MachineUnlearningProposal.ipynb`: Does not exist in the original repo. Used for the changes we implemented.

## Tuning

If you want to tune the hyperparameters, you should start with `tuning.ipynb`.

`src/fyemu_tunable` mainly exists to be able to tune the unlearning algorithm, but also serves as the main file which holds the whole FEMU+Gen Machine Unlearning Algorithm.
