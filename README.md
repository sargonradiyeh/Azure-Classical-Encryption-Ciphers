# Classical Encryption Ciphers Web Application

This project is an interactive web-based platform designed to explore and demonstrate classical encryption techniques. It is built as part of the EECE 455 course and showcases various ciphers with both educational and practical applications.

## Overview

The platform implements several classical encryption methods:

- **Affine Cipher**
  - Encryption and decryption with built-in methods for cracking using letter frequency analysis and top brute force.
- **Vigenère Cipher**
  - Encryption and decryption using a user-defined keyword.
- **Monoalphabetic Cipher**
  - Simple substitution cipher with validation to ensure key integrity.
- **Playfair Cipher**
  - Digraph-based encryption with dynamic key matrix generation.
- **Hill Cipher**
  - Block cipher encryption supporting 2x2 and 3x3 key matrices.
- **Extended Euclidean Algorithm**
  - Used for computing modular inverses essential for certain cryptographic operations.

## Features

- **User-Friendly Interface:**  
  Each cipher has its own dedicated page with clear instructions and input forms. The platform uses Django templates, HTML, and CSS to provide a seamless user experience.

- **Robust Backend:**  
  Python and Django handle encryption, decryption, and even methods for cracking ciphers. The project includes extensive error checking and input validation.

- **Educational Focus:**  
  The project not only implements these classical ciphers but also explains the underlying mathematical principles and vulnerabilities, making it a useful tool for learning cryptography.

## Technologies

- **Backend:** Django, Python
- **Frontend:** HTML, CSS
- **Deployment:** Azure Cloud

## Project Structure

- **Encryption Modules:**  
  Contains Python modules implementing encryption and decryption for each cipher.
  
- **Django Views & Forms:**  
  Handles user interactions, validates input, and processes encryption/decryption requests.

- **Frontend Pages:**  
  HTML and CSS files that define the user interface for each encryption method.

- **Testing & Results:**  
  Each cipher was tested with multiple cases to ensure correct functionality, including handling non-ASCII characters and edge cases in input.

## Team Members

- Sarjoun Radiyeh  
- Antoine Abu Faysal  
- Wael Dgheim  
- Adel El Kadi

## Documentation

For detailed project documentation including methodology, test results, and references, please see the full [EECE 455 Final Project Report](EECE_455_FINAL_PROJECT_REPORT.docx).

## Possible Future Enhancements

- Integrate additional encryption algorithms.
- Improve user interface design for enhanced usability.
- Expand testing and error handling for even more robust performance.
