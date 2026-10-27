# Mathematics for Robotics: Companion Notebooks

Interactive Jupyter notebooks for **_Mathematics for Robotics: A Beginner's Guide_**, a short textbook on the mathematics behind robot arms, written for beginners.

The book teaches everything algebraically and visually, with no code. These notebooks let you **run** each idea, change the numbers, and see what happens.

**By [ROSFORGE](https://rosforge.com)**, an autonomous robotics education platform.

## How the notebooks match the book

| Book chapter | Notebook |
|---|---|
| 1. Vectors and Matrices | `01_Vectors_and_Matrices.ipynb` |
| 2. Rotations | `02_Rotations.ipynb` |
| 3. Frames and Homogeneous Transforms | `03_Frames_and_Transforms.ipynb` |
| 4. Forward Kinematics | `04_Forward_Kinematics.ipynb` |
| 5. Derivatives and the Jacobian | `05_Jacobians.ipynb` |
| 6. Inverse Kinematics and Trajectories | `06_Inverse_Kinematics_and_Trajectories.ipynb` |

Section numbers inside each notebook follow the book. Every chapter's exercises are repeated at the end of its notebook, with a scratch cell for your attempt and a separate solution-check cell (the book's Appendix B, verified in code).

## Run it

```bash
pip install -r requirements.txt
jupyter lab
```

Then open a notebook and run the cells from top to bottom. You can also upload a notebook to Google Colab (the requirements are already available there).

## How to use them well

1. Read the chapter in the book first.
2. Run the notebook cell by cell. After each cell, change a number and run it again.
3. Do the exercises on paper, then check them in the solution cell.

## About ROSFORGE

ROSFORGE is an autonomous robotics education platform based in Tunisia, for engineering students and career changers learning ROS 2, navigation, SLAM and simulation. Website: [rosforge.com](https://rosforge.com)

## Feedback

Found a mistake, or something that could be clearer? Please let us know through [rosforge.com](https://rosforge.com).
