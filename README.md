# praktikum-RPS
Project ini menggunakan EfficientNetB3 sebagai model pretrain yang diambil menggunakan pustaka tensorflow.

Instalasi python version >= 3.10 dengan https://www.python.org/ftp/python/3.10.0/python-3.10.0-amd64.exe 

environment - path : 3.10 
Vscode : 
pip isntall flask . pip install tensorflow . pip install pillow . pip install opencv-2 
pip list python 
Setelah itu install semua requirements pip install -r requirements Lalu jalankan flask python app.py

Web dapat diakses dengan url http://127.0.0.1:2000 

Dataset Project ini menggunakan dataset rock paper scissor dengan jumlah data sebanyak 2520 file. Load image menggunakan image_dataset_from_directory dari pustaka tensorflow dengan pembagian train validation 80% dan test validation 20% dengan seed 123. Dataset menggunakan label categorical sehingga label dalam bentuk one hot encoding. Image size menggunakan (224, 244) dan batch size menggunkan 128



