# oc_with_rf

Open Clusters with Random Forest

This notebook is an attempt to reproduce the data analysis process as mentioned in Mahmudunnobe, M. et. al 2021 ([Membership of Stars in Open Clusters using Random Forest with Gaia Data.](https://doi.org/10.1140/epjs/s11734-021-00205-x)) to serve as a handout for the Master Seminar on [Dynamics of Galaxies, Star Clusters and Planetary Systems](https://wwwstaff.ari.uni-heidelberg.de/just/teaching/WS22/MVSem/) for the WS2022/23 at the Heidelberg University.

---
## Beginning guidelines

There are several pathways by which one can proceed with this repository.

1. Complete Novice to Open Clusters and Machine Learning:
   - Begin by checking the presentation, [MVSem_Bhavesh_Rajpoot.pdf](MVSem_Bhavesh_Rajpoot.pdf), on the paper.
  
   - Proceeding with [rf_in_action.ipynb](rf_in_action.ipynb)
  
2. Know Machine Learning but not Open Cluster or vice-versa:
   - Begin by checking the paper, [Membership of Stars in Open Clusters using Random Forest with Gaia Data.](https://doi.org/10.1140/epjs/s11734-021-00205-x)
  
   - Proceeding with [rf_in_action.ipynb](rf_in_action.ipynb)
  
3. Knows Machine Learning and Open Clusters:
   - Begin with [rf_in_action.ipynb](rf_in_action.ipynb) directly

Once you decide your pathway, you can proceed with these steps before running the notebook:

```
git clone https://github.com/Bhavesh012/oc_with_rf.git
cd oc_with_rf
```
```
conda env create --file=environment.yml
conda activate oc_with_rf
```

This project is currently in constant development and therefore can be updated with new methodologies or validation tests in the future. You can click on the "Watch" button in the top right for getting updates.

In the future, if you use these techniques in your work then please cite all the legible sources and this repo too.

For contributing to this project and repository, please see [collaboration.md](collaboration.md).

---
## References

### Papers

1. [Membership of Stars in Open Clusters using Random Forest with Gaia Data.](https://doi.org/10.1140/epjs/s11734-021-00205-x) by Mahmudunnobe, Md et. al. 2021
2. [A Gaia DR2 view of the open cluster population in the Milky Way](https://ui.adsabs.harvard.edu/abs/2018A%26A...618A..93C/abstract) by Cantat-Gaudin, T. et al 2018
3. [The GAIA Mission](https://ui.adsabs.harvard.edu/#abs/2016A%26A...595A...1G) by Gaia Collaboration et. al. 2016

### Packages

1. NumPy, AstroPy, Pandas, Matplotlib, Seaborn, Scikit-Learn
