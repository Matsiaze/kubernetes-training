# Deploying wordpress using the steps below:
Create a deployment mysql with 1 replica
#
Create a ClusterIP service to expose mysql pods
#
Create a deployment wordpress with env variable to connect to mysql database
#
Wordpress deployment should persist data on a mounted volume on local node
#
Create a NodePort service to expose wordpress frontend
