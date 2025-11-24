# 🌊 AI-JalRakshak: Water Quality Prediction Model

This project implements a machine learning model to predict water quality based on various physicochemical parameters. It is packaged with a simple web interface for user interaction.

## 🎯 Goal

The primary objective of this project is to use historical water quality data to train a classifier that determines whether a water sample is *Potable* (safe for drinking) or *Non-Potable*.

## 📁 Project Structure

The key files in this repository are:

* app.py: The main application file (likely a Flask or Streamlit app) responsible for loading the model and serving the web interface.
* model.py: Script used for training and evaluating the machine learning model.
* requirements.txt: Lists all necessary Python libraries (dependencies).
* water.csv: The dataset used for training the model.
* water_model.pkl: The saved, pre-trained model object.

## ⚙️ How to Run Locally

### 1. Prerequisites

You must have Python installed.

### 2. Setup

Clone the repository to your local machine:

```bash
git clone [https://github.com/anyharshu/AI-JalRakshak.git](https://github.com/anyharshu/AI-JalRakshak.git)
cd AI-JalRakshak
