# Lecture 3: Exploratory Data Analysis

Data Science and Machine Learning for Geoscientists  
Academic year: 2026–27  
Lecturer: Samaneh A. Mofrad

## About this lecture

We explore how to understand and visualise data before building models.
Using California earthquake data, we practise summarising and filtering
data, exploring relationships, and creating informative plots with
pandas, Matplotlib and seaborn.



## Learning materials

1. Start with [Lecture 3: Exploratory data analysis](01-Lecture3.ipynb).
2. Continue with [Exercise: Exploring the San Andreas Fault](02-San-Andreas-Fault.ipynb).

Keep the notebooks and their supporting `Datasets` and `img` folders
together so that data files and images load correctly.

Lecture slides and solutions will be added to this repository later.

## How to download the materials

You have two options:

1. **Download ZIP** — a straightforward way to download the materials.
2. **Use Git** — download the materials once, then retrieve updates
   without downloading the whole repository again.

You do not need a GitHub account to download this public repository
using either option.

### 1. Download ZIP

1. Click the green **Code** button near the top of this repository.
2. Select **Download ZIP**.
3. Extract (unzip) the downloaded folder.
4. Open JupyterLab or Jupyter Notebook on your computer.
5. Navigate to the extracted folder and open the lecture notebook.


You now have a local copy and can run and edit the notebooks
on your computer.


### 2. Use Git

If Git is not already installed, follow the [Git installation instructions](https://git-scm.com/install/) and select your operating system (Windows, macOS or Linux).

1. Click the green **Code** button near the top of this repository.
2. Select **HTTPS** and copy the repository link shown there.
3. Open a terminal in the location where you want to store the materials.
4. Type `git clone`, add a space, and paste the copied link:

   ```bash
   git clone PASTE_THE_COPIED_LINK_HERE
   ```

   Replace `PASTE_THE_COPIED_LINK_HERE` with the link you copied.

5. Press **Enter**. Git will create a folder containing the materials.
6. Open JupyterLab or Jupyter Notebook, navigate to that folder,
   and open the lecture notebook.

You now have the materials on your computer and can work locally.
An internet connection is needed to download updates and view linked videos.

### Getting updates with Git

If the contents of this repository will be changed, you do not need to download everything again.

Open a terminal **inside the cloned repository folder**.

To check for updates without changing your working files, run:

```bash
git fetch
git status
```

`git fetch` retrieves information and changes from GitHub without
applying them to your working files. `git status` then shows your
local changes and whether your branch is behind the downloaded updates.
Running `git status` alone does not check GitHub for new updates.

To apply the updates, run:

```bash
git pull
```

You can also run `git pull` directly without checking first.
If there are no updates, Git will report **Already up to date**.

These commands apply only to a folder created using `git clone`,
not to a folder downloaded as a ZIP.

### Keeping your exercise answers

Before starting the exercises, make a copy of each notebook in the
same folder and give it a different name, for example:

`01-Lecture3-my-answers.ipynb`

Work in this personal copy and keep the original notebooks unchanged.
This helps avoid conflicts when retrieving updates.

Updates will apply to the original course files; they will not
automatically change your personal notebook copies.



## Getting help

If you get stuck, ask the lecturer or a GTA.
Making mistakes and discussing them is part of learning.

## Acknowledgements

These materials build on resources developed by previous lecturers
and contributors to the Data Science and Machine Learning for
Geoscientists course at Imperial College London.
