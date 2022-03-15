This is a project template integrating different repositories that are usually present inside a REST-for-Physics project. Such as `detector-analysis`, `detector-simulations`, `detector-readouts`, `detector-geometry`, etc.

Those repository submodules are right now available at https://github.com/iaxo as private repositories. But as soon as they get generic enough they might be detached and placed at REST-for-Physics.

These template repositories are expected to be transformed using a *project-name*, i.e. `detector-analysis` might become `iaxod0-analysis`, `alphacamm-analysis`, `trexdm-analysis`, etc.

Here a brief description of the intention of each repository submodule:

* `detector-analysis`: It will contain configuration files defining a data chain for experimental data processing.
* `detector-simulations`: It will contain configuration files defining `restGH4` simulations (and eventually `detector-response`, or perhaps we will integrate the response in an independent repository?).
* `detector-readouts`: It will contain description of readout constructions (see also [basic-readouts](https://github.com/rest-for-physics/basic-readouts).
* `detector-geometry`: It will contain description of GDML geometries to be used on `restG4` simulations (see also [basic-geometries](https://github.com/rest-for-physics/basic-geometries).

If you use this repository as a template, remove the above lines and update the following ones fitting your project needs. You will need to update the submodules to point to your new repository submodules.

# Your project name

Write here a few words describing your project.

To clone this project do not forget to append `--recusive`

```
git clone git@github.com:rest-for-physics/detector-project.git --recursive
```

## Simulations

Write this section if required. Describe any simulations that can be launched using this repository.

Details will be foud at `detector-simulations` submodule. Give a link here.

## Analysis

Describe different analysis processing implemented 

### Plots

Describe any analysis plots used

## Instructions

Write here any instructions to help others starting to use this project.

Afterwards you can run analysis/simulations using standard REST programs.


**WARNING: REST is under continous development.** This README is offered to you by the REST community. Your HELP is needed to keep this file up to date. You are very welcome to contribute fixing typos, updating information or adding new contributions. See also our [Contribution Guide](https://github.com/rest-for-physics/framework/blob/master/CONTRIBUTING.md).

