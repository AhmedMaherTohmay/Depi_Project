# Final Project

This repository holds the AI components for a lung and colon image classification model. It includes various MLflow experiments of different models.

## Deployment Options

You have two deployment options:

* **Use Docker.**
* **Use python anywhere by uploading your files and running the app**.

## Repository Structure

This repository is divided into two parts:

## First part is for Chatbot Model

### The Chatbot model is made by the best model and integrated with front end

### 1. Model

#### Setup

1. **Clone the repository and create a virtual environment:**
   ```bash
   $ git clone https://github.com/AhmedMaherTohmay/Depi_Project.git
   $ cd project
   $ python3 -m venv venv
   $ . venv/bin/activate
   ```
2. **Install dependencies:**
   ```bash
   $ (venv) pip install Flask keras tensorflow
   ```

### 2. Frontend Integration

* **Static and Templates Folders:**
  * These folders contain the JavaScript, CSS, and HTML files used for this app.

## Deployment

* **Run the Flask app:**

```bash
  $ (venv) python app.py
```

  This command runs the main file, which contains the Flask API to run the app.
