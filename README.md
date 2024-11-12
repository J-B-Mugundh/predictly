# Predictly

## Overview
**Predictly** is an open-source machine learning project developed as part of [Google Developer Group on Campus MIT's](https://gdg.community.dev/gdg-on-campus-madras-institute-of-technology-chennai-india/) "Introduction to GitHub & Open Source Workshop". Built with Python and Streamlit, it provides a user-friendly interface for interacting with a diverse set of predictive models. Designed to empower users with customizable prediction calculators, **Predictly** makes it easy to build tailored tools for forecasting outcomes across various domains, from finance to healthcare.

## Current Status
The project is under active development with several machine learning models already implemented for various prediction tasks. The architecture is designed for dynamic configuration using JSON files, which map model parameters, inputs, and features. This design ensures new models can be seamlessly added or updated with minimal modification to the core codebase.

The project has been successfully tested in local environments, and current efforts are focused on enhancing integration, optimizing deployment, and improving scalability for production-ready applications.

## How to Contribute:
1. Review existing issues and contribute towards resolving them.
2. Or create new issues to discuss new ideas, suggest features, or report bugs.
3. Fork the repository and create a new branch for your contribution.
4. Implement your changes and submit a pull request with a clear description.
5. Futher details can be found in the [CONTRIBUTING.md](CONTRIBUTING.md) file.

## Setup Instructions
1. Fork or clone the repository.
2. Create a virtual environment and install the necessary dependencies:
   ```powershell
   python -m venv .venv
   .venv\Scripts\Activate
   ```
2. Install the necessary dependencies:
   ```powershell
   pip install -r requirements.txt
   ```
3. Run the Streamlit application using:
   ```powershell
   streamlit run app.py
   ```

