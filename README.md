# opfpy

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

**A collection of tutorials and implementations of important algorithms in the field of control and optimization of power systems.**

Each tutorial and implementation is provided as a [Python Notebook](https://jupyter.org/), with references to the original publication, and can be directly open in [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb). 

A full list of current implementations is provided [here](#current-implementations).

## Project Motivation
The fields of power system control and optimization is known for having a steep learning curve, especially for undergraduate students. Generally speaking, it often requires a strong background in:
 * electrical circuit theory
 * power system analysis
 * linear algebra
 * linear and nonlinear optimization

As someone who taught himself a lot of this material, I found an important lack of online resources (tutorials, public implementations, blog articles, etc.) compared to other currently popular fields (e.g., Machine Learning). I hope this project will contribute to bridging that gap.

## Who can opfpy be useful for?
I am a strong advocate of reproducing previous works from the literature to get a better understanding of a research field.

This repository is my attempt at learning about control and optimization in power systems, with a hands-on attitude, going in chronological order from the first important papers to today's research.

I believe ``opfpy`` can be useful for anyone looking to:
 * Start learning about power systems.
 * Get a better understanding of the core papers that have shapped the field as it is today.
 * Save time by not having to re-implement previous works.
 * Start using Python for modelling power systems (Python > MATLAB!).

## Contributing
I try to add the implementation of a new paper every week, but contributions are more than welcome! 

I also keep a list of papers that I intend to implement in the near future [here](#future-implementations). If you would like to implement any of those, or propose a non-listed paper, feel free to email me at robin.x.henry@gmail.com. Alternatively, you can also submit a [Pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests).

## Current Implementations
These paper implementations are classified into different categories and then organized in chronological order.

#### Load Flow Solution Methods
1. Hale, H., and J. Ward. "Digital computer solution of power flow problems." AIEE Transactions, pt. III (Power Apparatus and Systems) 75 (1956): 398-402. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/robinhenry/opfpy/blob/master/notebooks/Ward%20(1956)%20-%20Digital%20Computer%20Solution%20of%20Power-Flow%20Problems.ipynb)

## Future Implementations

#### Load Flow Solution Methods
1. Brown, R. J., & Tinney, W. F. (1957). Digital solutions for large power networks. Transactions of the American Institute of Electrical Engineers. Part III: Power Apparatus and Systems, 76(3), 347-351.

2. Glimn, A. F., & Stagg, G. W. (1957). Automatic calculation of load flows. Transactions of the American Institute of Electrical Engineers. Part III: Power Apparatus and Systems, 76(3), 817-825.

3. Brown, H. E., Carter, G. K., Happ, H. H., & Person, C. E. (1963). Power flow solution by impedance matrix iterative method. IEEE transactions on power apparatus and systems, 82(65), 1-10.

4. Tinney, W. F., & Hart, C. E. (1967). Power flow solution by Newton's method. IEEE Transactions on Power Apparatus and systems, (11), 1449-1460.

5. Peschon, J., Piercy, D. S., Tinney, W. F., Tveit, O. J., & Cuenod, M. (1968). Optimum control of reactive power flow. IEEE Transactions on Power Apparatus and Systems, (1), 40-48.

## Bug Reports
Feel free to create a new issue on this repository if you spot any bug. You can also email me at robin.x.henry@gmail.com
