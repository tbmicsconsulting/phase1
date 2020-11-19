# FEAT Fairness Methodology: Marketing System Assessment

This repository provides Jupyter notebooks and supporting code for the
marketing case study assessment in the FEAT Fairness Principles Assessment Case
Studies Document. Please see Section 2.3 of that document for the marketing
case study assessment itself. This code is not intended for use in production
or for assessing high risk AIDA systems under the methodology.

This work was undertaken as part of the Veritas initiative commissioned by the
Monetary Authority of Singapore, whose goal is to accelerate the adoption of
responsible Artificial Intelligence and Data Analytics (AIDA) in the financial
services industry.

## Contents

The key files are the following:

- `assessment_input.ipynb`: generates the analysis for the assessment
- `uplift_simulation.ipynb`: generates the synthetic data for the system being
  assessed
- `*.py`: Python code providing functionality to support the above notebooks
- `*.csv`: Synthetic data generated by the simulation

## Installation

The `requirements.txt` provides the Python prerequisites for running the
notebooks. These can be installed in a virtualenv, for example with:

  pip install -r requirements.txt

Then, run `jupyter notebook` from the root directory of the repository and
open the notebooks.

## Copyright

Written by Daniel Steinberg and Lachlan McCalman, Gradient Institute Ltd.
![info@gradientinstitute.org](mailto:info@gradientinstitute.org).

Copyright © 2020 Monetary Authority of Singapore.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use
this file except in compliance with the License. You may obtain a copy of the
License at

![http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed
under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR
CONDITIONS OF ANY KIND, either express or implied. See the License for the
specific language governing permissions and limitations under the License.