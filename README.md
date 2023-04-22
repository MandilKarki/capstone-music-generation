# Music Generation with RNN and VAE
This project aims to generate and continue music using various machine-learning models. Specifically, we utilize the Long Short-Term Memory (LSTM) model and the Variational Autoencoder (VAE) for music generation. Our LSTM architecture includes 1024 Recurrent Neural Network (RNN) units and is initialized with the Glorot uniform distribution. The input music tokens are first passed through a learnable embedding layer to create 256-dimensional vectors, which are then recursively fed into the LSTM layer.  

This project is the master repository which contains frontend and and backend
Firstly clone the project
For backend 
```
git clone backend with branch name API-Integratioin
```
git clone https://github.com/fagami1423/music_generation/tree/API-Integratioin
```
git clone https://github.com/fagami1423/music_frontend
```

Run the following master run commands

```
docker compose up
```
For Frontend
```
http://localhost:3000
```
For Backend
```
http://localhost:8000/docs
or 
http://localhost:8000/redoc

```