This repository contains code, analyses, and supplementary material accompanying our paper:

>  False Promises in Medical Imaging AI? Assessing Validity of Outperformance Claims
>  Evangelia Christodoulou, Annika Reinke, Pascaline Andrè, Patrick Godau, Piotr Kalinowski, Rola Houhou, Selen Erkan,
> Carole H. Sudre, Ninon Burgos, Sofiène Boutaj, Sophie Loizillon, Maëlys Solal, Veronika Cheplygina, Charles Heitz,
> Michal Kozubek, Michela Antonelli, Nicola Rieke, Antoine Gilson, Leon D. Mayer, Minu D. Tizabi,   M. Jorge Cardoso, Amber Simpson,
> Annette Kopp-Schneider, Gaël Varoquaux, Olivier Colliot, Lena Maier-Hein 
> Submitted to *Nature Biomedical Engineering*, 2025  


---



## 📁 Repository Structure

├── deviations.ipynb # Analysis on private classification dataset ├── segmentation_analysis_msd.ipynb # Analysis on private segmentation dataset (MSD) ├── false_claim_probability.ipynb # Simulations for probability of false claims ├── utils/ # Helper functions (e.g., evaluation metrics, plotting) ├── environment.yml # Conda environment (optional) └── README.md # You’re here!

yaml
Copy
Edit

---

## 🧪 Notebooks

| Notebook                      | Description |
|------------------------------|-------------|
| `deviations.ipynb` | Initial analysis on the private classification dataset. |


All notebooks are meant to be exploratory and illustrative — further scripts or pipelines will be added upon manuscript acceptance.

---

## 🔐 Data Access

The datasets used in this work are **private and not shared in this repository** due to licensing restrictions:

- **Classification dataset**: Institutional data with restricted access.
- **Segmentation dataset (MSD)**: Derived from the [Medical Segmentation Decathlon](http://medicaldecathlon.com/), but processed variants used here are not publicly released.
- **Simulations** are fully reproducible.

Please contact the authors for data-sharing inquiries where permissible.

---


