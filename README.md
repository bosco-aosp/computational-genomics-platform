## On-line documentation on [“Computational genomics platform” using Galaxy](https://tgiangregorio.github.io/computational-genomics-platform)

### Updating GitHub Pages - for Admins only
Automatic update of GitHub pages through Jekyll is disabled. To update pages you have to build the website locally and push the updated pages:

 * Clone this repository with `git clone https://github.com/sigu-training/clinical_genomics.git`
 * (If not done yet) Set up the conda environment - see this [tutorial](https://galaxyproject.github.io/training-material/topics/contributing/tutorials/running-jekyll/tutorial.html) for details:
   * Move to the cloned repository with `cd clinical_genomics`
   * Install conda, if not already installed: `make install conda`
   * Create the **galaxy_training_material** conda environment: `make create-env`
   * Install Jekyll and related modules into the conda environment: `make install`
 * Build the website locally with `make build` (static) or `make serve` (interactive). This will generate the new HTML Pages in the *docs* folder.
 * Push the updated files. 

When updating text, please follow the [formatting instructions](https://sigu-training.github.io/clinical_genomics/syntax.html).

### Contributors
 * Tania Giangregorio - Sant’Orsola-Malpighi University Hospital, Bologna, Italy
 * Federica Isidori - Sant’Orsola-Malpighi University Hospital, Bologna, Italy
 * [Tommaso Pippucci](http://oldwww.aosp.bo.it/content/curriculum?E=154659) - Sant’Orsola-Malpighi University Hospital, Bologna, Italy
