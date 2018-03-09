> **If you use the resources (algorithm, code and dataset) presented in this repository, please cite our paper.**  
*The BibTeX entry is provided at the bottom of this page. 

# CAPRA: A contour-based accessible path routing algorithm
Existing journey planners and route recommenders mainly focus on calculating the shortest path with minimum distance or travel time. However, elderly people and those with special needs (i.e. those in wheelchairs or walking with sticks) often prefer a safer and more gentle journey. Given that their route options are affected by accessibility issues such as climbing a steep slope, it is important to design a journey planner that takes in to account the accessibility of the route, as well as the standard metrics, such as travel time and distance. Accessibility has not been explored widely in path finding problems. There are two key challenges for computing accessibility. First, the accessibility of a route is not well-defined. Second, the accessibility of a route varies from user to user. In this paper, a new algorithm is designed to tackle the above two challenges. Two metrics are defined to reflect the accessibility of a route, in terms of the total vertical distance and the maximum slope. Then, a multi-objective A* search algorithm is designed to obtain a set of Pareto-optimal routes in terms of the total distance covered and the two accessibility metrics. The user can then choose from the routes provided by the new algorithm, the most suitable one according to their own preferences. The experimental results show that the proposed algorithm is able to provide a diverse set of routes with different accessibility options, including the shortest path which does not consider any accessibility metrics. In other words, the new journey planner can satisfy the preferences of a wide range of users including both the healthy and those with special needs.

This repository contains resources developed within the following paper:

	Rahaman, M. S., Mei, Y., Hamilton, M., & Salim, F. D. (2017). CAPRA: A contour-based accessible path routing algorithm.  
	Information Sciences, 385, 157-173.

You can find the [paper](https://github.com/cruiseresearchgroup/CAPRA-Accessible-Path-Routing/blob/master/paper/rahaman2017capra.pdf) in this repository. 

Alternative link: https://www.sciencedirect.com/science/article/pii/S0020025516322745

## Contents of the repository
This repository contains resources used and described in the paper.

The repository is structured as follows:

- `code/`: The folder containing "capra", an eclipse (java) project. 
- `data/`: Dataset used for this paper. 
- `paper/`: Formal description of the algorithm and evaluation result. 

## Citation
If you use the resources presented in this repository, please cite (using the following BibTeX entry):
```
@article{rahaman2017capra,
  title = "CAPRA: A contour-based accessible path routing algorithm ",
  journal = "Information Sciences",
  volume = "385–386",
  pages = "157 - 173",
  year = "2017",
  issn = "0020-0255",
  doi = "https://doi.org/10.1016/j.ins.2016.12.041",
  url = "https://www.sciencedirect.com/science/article/pii/S0020025516322745",
  author = "Mohammad Saiedur Rahaman and Yi Mei and Margaret Hamilton and Flora D. Salim",
  keywords = "Journey planning",
  keywords = "Accessible path",
  keywords = "Route ranking",
  keywords = "Path routing",
  keywords = "Multi-objective A* algorithm "
}
```
