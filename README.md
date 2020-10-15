# Deploy-Deep-Learning-Models-TF-Serving-Docker-gRPC-REST

The dataset for TensorFlow Serving with Docker for Model Deployment is available [here](https://drive.google.com/file/d/14v42um2VRAfQPfGnBJ4QzOie4VZOPK_F/view
).

## Project Flow 

1. Import model tf2-preview/nnlm-en-dim128 from Tensorflow Hub 
2. Freeze the imported model and train single dense layer
3. Export the Model as Protobuf
4. Start TensorFlow Serving with Docker
5. Setup a client (either gRPC or REST based)
6. Run the client
7. We predict Amazon product ratings based on plaintext reviews using gRPC or REST client.
  
 This is the project done from Coursera Project Network [course](https://www.coursera.org/projects/tensorflow-serving-docker-model-deployment) 
