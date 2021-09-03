{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "52ef785e",
   "metadata": {},
   "source": [
    "# Exercise 1 - Linear Regression with Python"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "25fe1907",
   "metadata": {},
   "source": [
    "We will use a set of data $(x,y)$ and apply Gradient Descent to get a fitted line $L(x) = \\theta_0 + \\theta_1 x$ that will minimize the cost function $J(\\theta)$\n",
    "\n",
    "##Libraries\n",
    "-numpy\n",
    "-pandas\n",
    "\n",
    "First we will import the necessary libraries"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 10,
   "id": "8924e41e",
   "metadata": {},
   "outputs": [],
   "source": [
    "import numpy as np\n",
    "import pandas"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e68255bb",
   "metadata": {},
   "source": [
    "Import data ex1data1.txt into Python"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 11,
   "id": "57f9ac9b",
   "metadata": {},
   "outputs": [],
   "source": [
    "data=pandas.read_csv('ex1data1.txt',sep=',',na_values='.')"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 12,
   "id": "3946565c",
   "metadata": {},
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "     6.1101    17.592\n",
      "0    5.5277   9.13020\n",
      "1    8.5186  13.66200\n",
      "2    7.0032  11.85400\n",
      "3    5.8598   6.82330\n",
      "4    8.3829  11.88600\n",
      "..      ...       ...\n",
      "91   5.8707   7.20290\n",
      "92   5.3054   1.98690\n",
      "93   8.2934   0.14454\n",
      "94  13.3940   9.05510\n",
      "95   5.4369   0.61705\n",
      "\n",
      "[96 rows x 2 columns]\n"
     ]
    }
   ],
   "source": [
    "print(data)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e41f8e2b",
   "metadata": {},
   "source": [
    "Define our training sets to be $X$=input and $y$=output\n",
    "\n",
    "Note: Since $X\\theta = y$, the first column of $X$ will always be a column of ones to correspond to the first parameter $\\theta_0$ of $\\theta = \\begin{bmatrix} \\theta_0 \\\\ \\theta_1 \\end{bmatrix}$"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "9ee677f5",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.9.0"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
