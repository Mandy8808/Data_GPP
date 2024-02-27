## Numerical Profiles data

Folders:
- Jupyter_Notebook_profiles: This folder contain the Jupyter notebook "Profiles.ipynb" (along with two modules), which describes the procedure for obtaining and constructing the data-tables. At the end of the notebook, we present an example of how system (2.12) in [arXiv:2211.08433](https://arxiv.org/pdf/2211.08433.pdf) and system (9) in [arXiv:2402.07998](https://arxiv.org/pdf/2402.07998.pdf) are equivalent, using the rescaled approach. 

- Data: This folder contains two subfolders, "ground_state" and "first_excited_state," which include tables with the structure

| E | r_ours | U_our | sigma_ours |	Psi_ours(t=0) |	dot_Psi_ours(t=0) |	r_yours |	U_yours |	sigma_yours |	Psi_yours(t=0) |	dot_Psi_yours(t=0)|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |

Notice that the suffix *_ours* is used to indicate that the quantities are expressed in our units (as described in [arXiv:2402.07998](https://arxiv.org/pdf/2402.07998.pdf)), while *_yours* indicates that the quantities have been rescaled (as described in the PDF notes) to be consistent with the notation in [arXiv:2211.08433](https://arxiv.org/pdf/2211.08433.pdf). The quantity E is the same in both notations.

The names of the tables are table_%, where the number indicates the index of the central amplitude $\sigma_0=[1.0, 1.1, 1.2, 1.3, 1.4, 1.5, 1.6, 1.7, 1.8, 1.9, 2. , 2.1, 2.2, 2.3]$

COMMENT: The temporal component is described by the harmonic ansatz Eq. (16) in [arXiv:2402.07998](https://arxiv.org/pdf/2402.07998.pdf).
