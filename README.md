# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations
### Step 2: Prepare the lists from each linear equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
## Developed By: VASANTH N
## Register Number: 24000697

        import numpy as np       
        a = np.array([[2,-3,0],[2,-5,0],[0,0,3]])      
        value,vector = np.lialg.eig(a)       
        print("Eigen values are",values,"and Eigen Vector are",vector)      

## Output:
![WhatsApp Image 2024-12-04 at 14 08 20_b721068e](https://github.com/user-attachments/assets/049c4cd5-093f-4df5-8dd1-1d06b4ef168d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
