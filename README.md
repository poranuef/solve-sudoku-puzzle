### Sudoku puzzle solving using image processing techniques

This program serves as a way to calculate the solution to any 9x9 sudoku puzzle via puzzle picture, It identifies the puzzle through the picture, processes it uses OpenCV, runs against a convolutional neural network to predict the digits, and runs an py-sudoku to determine the answer. It then displays the answer on the same frame if it is solvable.

##### Contents
* Folder data use to evaluate model.
* Folder puzzle use to test this program.
* model.ipynb use to create and save model.
* solve_sudoku.ipynb use to solve sudoku puzzle.
* model.h5 is a model to predict the digits.

##### Technology Used
* OpenCV
* Tensorflow
* py-sudoku

###### Input
![HbwIOz.png](https://sv1.picz.in.th/images/2022/05/21/HbwIOz.png)


###### Output
![HbwMX8.png](https://sv1.picz.in.th/images/2022/05/21/HbwMX8.png)