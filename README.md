# Neural-Control-Tools
Welcome to the landing page for projects supporting our neural control research. These projects focus on data-driven nonlinear optimal control of the physical cartpole robot and our INIvincible F1Tenth race car.

## Our Repositories:

- [SI_Toolkit](https://github.com/SensorsINI/SI_Toolkit)
- [Control_Toolkit](https://github.com/SensorsINI/Control_Toolkit)
- [CartPoleSimulation](https://github.com/SensorsINI/CartPoleSimulation)
- [physical-cartpole](https://github.com/SensorsINI/physical-cartpole)
- [ControlGym](https://github.com/SensorsINI/ControlGym)
- [F1Tenth-INI](https://github.com/F1Tenth-INI)

## Publications
* [Hardware Neural Control of CartPole and F1TENTH Race Car](https://arxiv.org/abs/2407.08681)
* [RPGD: A Small-Batch Parallel Gradient Descent Optimizer with Explorative Resampling
for Nonlinear Model Predictive Control](https://www.zora.uzh.ch/id/eprint/254218/1/RPGD_ICRA_2023.pdf)

## Dependencies:

All dependencies between the repositories are automatically managed in the form of Git submodules. For example, if you clone the `physical-cartpole` repository, it will include the `CartPoleSimulation`, and `CartPoleSimulation` will include `SI_Toolkit` and `Control_Toolkit`. Unlike other repositories, `SI_Toolkit` is a Python library and needs to be installed. This happens automatically when running `pip install -r requirements.txt`.

The dependencies are visualised on the chart below. [f1tenth_development_gym](https://github.com/F1Tenth-INI/f1tenth_development_gym) and [f1tenth_system](https://github.com/F1Tenth-INI/f1tenth_system) are accessible through [F1Tenth-INI](https://github.com/F1Tenth-INI).
![Dependencies between our repositories](https://github.com/SensorsINI/Neural-Control-Tools/blob/main/Dependencies.png)
