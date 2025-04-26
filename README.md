# Automated Image Processing System Using AWS Lambda and S3

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📌 Overview
This project automatically processes images uploaded to an AWS S3 bucket using AWS Lambda. It resizes the image and stores it in another bucket.

## 🛠️ Technologies Used
- AWS Lambda
- AWS S3
- AWS IAM
- Python 3.9
- Boto3
- Pillow

## 🏗️ Architecture
![Architecture Diagram](architecture-diagram.png)

## 📂 Folder Structure
- `lambda/` - Lambda function code.
- `screenshots/` - Setup screenshots.
- `deployment-guide.md` - Step-by-step setup guide.

## 🚀 How to Deploy
See [`deployment-guide.md`](deployment-guide.md).

## 📜 License
MIT License
