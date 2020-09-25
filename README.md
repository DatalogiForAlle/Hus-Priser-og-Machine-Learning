# Hus Priser og Machine Learning
Dette projekt indeholder kode som bruges til at 

# Kør med Binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/DatalogiForAlle/Hus-Priser-og-Machine-Learning/master?filepath=housing.ipynb)

# Development

`requirement.txt` only lists requirements necessary for running Binder.

During development on this repo, these additional requirements are needed:

```
jupyter
nbstripout
```

We use `nbstripout` to avoid huge commits with Jupyter notebook cell
gdata. A command needs to be run to install `nbstripout` in your local
`git` repository, to make it automatically remove those values from
commits:

```
nbstripout --install
```

Read more at https://github.com/kynan/nbstripout
