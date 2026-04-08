# 🌐 Kick-off code for building a multidigraph and extracting frequent subgraphs from it

## Created by
**Author:** Hugo Alatrista-Salas <br />
**Co-authors:** Gaël Chareyron, Sonia Djebali, Imen Ouled-Dlala and Nicolas Travers  <br />
**Maintainer:** Hugo Alatrista-Salas <br />
**Contact Details:** hugo.alatrista_salas@devinci.fr <br />
**Institution:** De Vinci Higher Education, De Vinci Research Center, Paris, France 
<br />

**Note:** Use Python 3.9.*

## Description

This code enables the construction of a multidigraph representing tourist movement in Lille, France. 
Then, the multidigraph is simplified by removing multiple edges and self-loops. 
The simplified graph is used as input for frequent subgraph mining through the PAMI library.

The dataset used to demonstrate this code has been used in previous works by the authors. 

## Citation

If you use this code or find it helpful in your research, please cite:

```bibtex
@Article{Alatrista-Salas2025,
author={Alatrista-Salas, Hugo
and Chareyron, Ga{\"e}l
and Djebali, Sonia
and Ouled Dlala, Imen
and Travers, Nicolas},
title={SeqPatTour: sequential patterns-based metrics for better understanding the tourism behaviour},
journal={Quality {\&} Quantity},
year={2025},
month={Dec},
day={22},
doi={10.1007/s11135-025-02501-3},
url={https://doi.org/10.1007/s11135-025-02501-3}
}
