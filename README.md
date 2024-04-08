# Modulus on HPG
This tutorial is adapted from GitHub repositories [modulus/examples/molecular_dynamics](https://github.com/NVIDIA/modulus/tree/main/examples/molecular_dynamics/lennard_jones) and [Nvidia Modulus Document](https://docs.nvidia.com/deeplearning/modulus/modulus-sym/index.html).

## Modulus Introduction
NVIDIA Modulus Sym is a deep learning framework that blends the power of physics and partial differential equations (PDEs) with AI to build more robust models for better analysis.

There is a plethora of ways in which ML/NN models can be applied for physics-based systems. These can depend based on the availability of observational data and the extent of understanding of underlying physics. Based on these aspects, the ML/NN based methodologies can be broadly classified into forward (physics-driven), data-driven and hybrid approaches that involve both the physics and data assimilation.

With NVIDIA Modulus Sym, we aim to provide researchers and industry specialists, various tools that will help accelerate your development of such models for the scientific discipline of your need. Experienced users can start with exploring the Modulus Sym APIs and building the models while beginners can use this User Guide as a portal to explore the possibilities of AI in the domain of scientific computation. The User Guide comes in with several examples that will help you jumpstart your development of AI driven models.

Modulus code is open source and packaged in a modular fashion into two repos - Modulus Core and Modulus Sym. For more information, please refer to the **[Nvidia Modulus Getting Started](https://docs.nvidia.com/deeplearning/modulus/getting-started/) page**.

## Quick Start Modulus on HiPerGator (HPG)
[Modulus NGC Container](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/modulus/containers/modulus) has been installed on HPG and deployed as modules and kernels. You can load the latest Modulus module on HPG terminal using 'module load modulus' or in the Jupyter Notebook with the 'modulus/24-01' kernels. To check other available versions of Modulus, you can use "module spider modulus" command.

## Two Modulus examples:
**01. Solve a given PDE with boundary conditions (BC) using Modulus via Jupyter Notebook:** This entry-level example solves a pure physics-driven problem with Modulus. It is used to show the general workflow of Modulus.

**02. Use Multi-GPUs to run parallel molecular dynamics job using Modulus on HPG:** This example illustrates the use of the MeshGraphNet model to develop a DL model for predicting forces or potential for a Lennard-Jones System as described in the [paper here](https://arxiv.org/abs/2112.03383). We use this example to show how to run Multi-GPU Modulus jobs on HPG.

## License
All rights are reserved to the [Nvidia Modulus](https://docs.nvidia.com/modulus/index.html) team.
   
