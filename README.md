# BDT-Wheel

This is my template for creating a wheel file from the `egg` file included as part of the Big Data Toolkit. It _does
not_ include the Big Data Toolkit. Rather, it just provides the scaffolding to unpack the `egg` file and build a
wheel file.

## Steps

1. Clone this repository.
2. Using 7-Zip, open and extract the `bdt` directory and place it in the `src` directory in the project tree.
3. Ensure `build` is installed in the current Python environment. This can be installed using `conda install build`
   or `pip install build`.
4. Create the wheel using `build --wheel`. The wheel will be created in the `dist` directory in the root of the
   project tree.

