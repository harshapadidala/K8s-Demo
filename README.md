# K8s-Demo

Create components in order, first external configurations configMap and secret, then mongodb and webapp

kubectl apply -f mongo-config.yaml

kubectl apply -f mongo-secret.yaml

kubectl apply -f mongo.yaml

kubectl apply -f webapp.yaml