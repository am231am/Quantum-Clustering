## Quantum K-Means Clustering

This repository implements the K-means clustering algorithm using quantum state encoding for classical data points, and encode it to Quntum .

### Functions
#### 1. generate_random_data
Generates a NumPy array of random data with one column < Ket>

#### 2. ground_state
Returns a NumPy array representing the ground state (|0> state).

#### 3. initialize_centroids
Randomly initializes k centroids from the data points.

#### 4. encode_data
Encodes classical data points into quantum states using an RXGate.

#### 5. findClosestCentroids
Computes the centroid memberships for every encoded data point.

#### 6. computeCentroids
Returns the new centroids by computing the means of the data points assigned to each centroid.

#### 7. K_means_Quantum_clustering
Performs K-means clustering on classical data points using quantum state encoding.

### Usage

1-Generate Random Data

2-python

3-from qiskit.circuit.library import XGate

4-import numpy as np

### def generate_random_data(m: int, n: int) -> np.array:
    ...
Ground State
def ground_state() -> np.array:
    ...
### Initialize Centroids

### def initialize_centroids(data: np.array, k: int) -> np.array:
    ...
Encode Data
def encode_data(data: np.array, ground_state: np.array) -> np.array:
    ...
Find Closest Centroids

### def findClosestCentroids(enc_data: np.array, enc_centr: np.array) -> np.array:
    ...
Compute Centroids

### def computeCentroids(enc_data: np.array, idx: np.array, K: int) -> np.array:
    ...
K-Means Quantum Clustering

### def K_means_Quantum_clustering(data: np.array, k: int) -> np.array:
    ...
#### Installation
You can install the required libraries using pip:

pip install qiskit matplotlib

### Contact
For any inquiries or suggestions, please contact the author at nourraafat51@gmail.com.
