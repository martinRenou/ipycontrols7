
# ipycontrols7

Installation:

```
micromamba install jupyterlab=4 ipywidgets=8 -c conda-forge

pip install ipycontrols7
```

![Screenshot from 2024-07-04 10-57-27](https://github.com/martinRenou/ipycontrols7/assets/21197331/780d66c6-2b1c-4a1d-ba72-70a8c2952c03)


This hack required patches on `@jupyter-widgets/controls` to make CSS not collide between old and new versions of widgets, see https://github.com/martinRenou/ipywidgets/commit/2412504e27b52e5f3078d8196ced2943c881d9b3. These patches are published on NPM as https://www.npmjs.com/package/jupyter-controls7.
