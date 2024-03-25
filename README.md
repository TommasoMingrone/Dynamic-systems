# Dynamic Systems Project

## Authors
- Elisa Coceani
- Tommaso Mingrone

## Project Overview
This project explores a dynamic system characterized by the competition between two populations, specifically rabbits and sheep, over shared resources. The system is modeled by the differential equations:

\dot{x} = x(3 - ax - by)
\dot{y} = y(2 - x - y)


where `x` and `y` represent the populations of rabbits and sheep, respectively, and `a` and `b` are parameters affecting the interaction between the two populations.

## Objective
The main objective of this study is to analyze the behavior of the system under various conditions, particularly varying the parameters `a` and `b` within certain ranges. The analysis focuses on identifying and understanding the system's fixed points, their stability, and the implications of these on population dynamics.

## Key Features
- Definition and exploration of the dynamic system.
- Identification and stability analysis of the system's fixed points.
- Visualization of phase portraits and vector fields to illustrate system behavior.
- Non-linear expansion and manifold analysis.

## Installation and Usage
To run the analysis presented in this project, ensure that you have Python installed along with the necessary scientific libraries, namely NumPy, Matplotlib, and SciPy. Clone this repository to your local machine, navigate to the project directory, and run the Jupyter notebook:

```bash
git clone [repository-url]
cd [project-directory]
jupyter notebook "Dynamic systems project - Elisa Coceani, Tommaso Mingrone.ipynb"
```
## Results and Discussion

The analysis identified four equilibrium points with varying stability, which are discussed in detail within the notebook. Phase portraits and vector fields are generated to provide insights into the dynamics of the rabbit and sheep populations. Additionally, the effects of non-linear expansions on the system's behavior are examined.

## Conclusion

The dynamic system study reveals significant insights into the interactions between competing populations. The stability analysis of fixed points helps in understanding the possible long-term behaviors of the system under different conditions.
