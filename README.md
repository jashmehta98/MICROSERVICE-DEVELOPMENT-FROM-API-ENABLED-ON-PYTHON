# MICROSERVICE-DEVELOPMENT-FROM-API-ENABLED-ON-PYTHON
There will be two Docker files for the two apps and upload (push) the images to ECR using AWS cli commands. The ALB gets request on port 80 and depending on the path, it will redirect the request to the proper app: "/" to home and "/blog" to our blog app, depending on load on servers.
