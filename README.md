# Hash Function Research Project

This project is aimed at decrypting a dataset encrypted using a hash function with the utilization of an input identifier - a salt. Additionally, it involves analyzing the solution to a similar problem under various conditions.

## Task Description

The goal of the project is to decrypt a dataset encrypted using a hash function with the help of an input identifier - a salt, and to analyze the solution to a similar problem under different conditions.

## Implementation

The provided Python code accomplishes the following tasks:

1. **Loading Data:** Allows loading a dataset from an Excel file.
2. **Identifying Hashes:** Identifies the hashes present in the dataset and computes relevant salts.
3. **Salt Computation:** Computes the salt value based on the provided hashes and numbers.
4. **Encryption:** Implements encryption using SHA-1, SHA-256, and SHA-512 algorithms.
5. **Graphical User Interface (GUI):** Provides a user-friendly interface for performing the above tasks.

## Usage

1. **Load Data:** Click the "Load" button to load the dataset from an Excel file.
2. **Identify Hashes:** After loading the data, click the "Deidentify" button to identify hashes and compute salts.
3. **Compute Salt:** Click the "Compute Salt" button to calculate the salt value.
4. **Encrypt Data:** Choose an encryption algorithm (SHA-1, SHA-256, or SHA-512) and click the corresponding button to encrypt the data.

## How to Run

To execute the code:
1. Ensure you have Python installed on your system.
2. Install the necessary dependencies (`pandas`, `tkinter`).
3. Run the provided Python script (`main.py`).
