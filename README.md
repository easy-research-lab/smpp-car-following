# SMPP Car-Following

**Microscopic Traffic Simulation and Car-Following Models for Connected and Automated Vehicles**

This repository contains research code developed as part of the **European Commission Joint Research Centre (JRC) Smart Mobility Project Portfolio (SMPP)**, particularly the **Requirements and Implications of a Connected and Automated Mobility (RICAM)** project. The research contributed to understanding the impact of connected and automated vehicles on traffic flow, road capacity, stability, energy consumption, and transport efficiency, through modelling, simulation, and empirical validation.

The research focuses on modelling, simulating, and evaluating car-following behaviour, Adaptive Cruise Control (ACC), traffic flow stability, road geometry effects, and vehicle dynamics.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/easy-research-lab/smpp-car-following.git
cd smpp-car-following
```

### 2. Create the Conda Environment

Create a virtual environment using the provided configuration file [`environment.yml`](https://github.com/easy-research-lab/smpp-car-following/blob/master/environment.yml):

```bash
conda env create -f environment.yml
```

To identify the environment name, open `environment.yml` and check the `name:` field.

Activate the environment:

```bash
conda activate <environment-name>
```

Replace `<environment-name>` with the name specified in `environment.yml`.

### 3. Usage

After activating the Conda environment, open the relevant Python scripts or Jupyter notebooks in your preferred development environment, such as VS Code or JupyterLab, depending on the files provided in the repository.

For reproducible research:

1. Select the relevant model or simulation workflow.
2. Configure the required input data, model parameters, and simulation settings.
3. Run the corresponding implementation.
4. Analyse the generated trajectories, model predictions, or evaluation results.
5. Refer to the associated publications for model formulations, calibration procedures, and validation methodology.

**Note:** Entry-point scripts, input-file requirements, and example commands should be documented for each implementation. The specific executable files have not yet been verified.

## Citation

```bibtex
@article{dona2022multianticipation,
  title={Multianticipation for string stable Adaptive Cruise Control and increased motorway capacity without vehicle-to-vehicle communication},
  author={Don{\`a}, Riccardo and Mattas, Konstantinos and He, Yinglong and Albano, Giovanni and Ciuffo, Biagio},
  journal={Transportation Research Part C: Emerging Technologies},
  volume={140},
  pages={103687},
  year={2022},
  publisher={Elsevier}
}

@article{he2022physics,
  title={Physics-augmented models to simulate commercial adaptive cruise control (ACC) systems},
  author={He, Yinglong and Montanino, Marcello and Mattas, Konstantinos and Punzo, Vincenzo and Ciuffo, Biagio},
  journal={Transportation Research Part C: Emerging Technologies},
  volume={139},
  pages={103692},
  year={2022},
  publisher={Elsevier}
}

@article{he2021introducing,
  title={Introducing the effects of road geometry into microscopic traffic models for automated vehicles},
  author={He, Yinglong and Mattas, Konstantinos and Dona, Riccardo and Albano, Giovanni and Ciuffo, Biagio},
  journal={IEEE transactions on intelligent transportation systems},
  volume={23},
  number={8},
  pages={13604--13613},
  year={2021},
  publisher={IEEE}
}

@article{he2024introducing,
  title={Introducing hybrid vehicle dynamics in microscopic traffic simulation},
  author={He, Yinglong and Mattas, Konstantinos and Makridis, Michail A and Komnos, Dimitrios and Marin, Andres L and Fontaras, Georgios and Ciuffo, Biagio},
  journal={IEEE transactions on intelligent transportation systems},
  volume={25},
  number={7},
  pages={7977--7986},
  year={2024},
  publisher={IEEE}
}

```

## Acknowledgements

This work was conducted within the European Commission Joint Research Centre (JRC) Smart Mobility Project Portfolio, particularly the RICAM project, with contributions from collaborating researchers and institutions.


## License

See the LICENSE file for details.
