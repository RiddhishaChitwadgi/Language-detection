# Language Detection Model

This repository contains code for a language detection model deployed on Heroku using FastAPI.

## Overview

The language detection model is designed to identify the language of a given text. It uses a pre-trained machine learning model to make predictions. The model is exposed through a FastAPI web application and deployed on Heroku for easy accessibility.

# Language Detection Model Deployment Guide

Follow these steps to deploy the language detection model on Heroku using FastAPI.

## Clone Repository

```bash
git clone https://github.com/your-username/language-detection.git
```
## Install Dependencies

```bash
cd language-detection
pip install -r requirements.txt
```
## Deploy Heroku

```bash
heroku login
heroku create your-heroku-app-name
git push heroku master
```
## Access Deployed Model

```bash
heroku open
```
