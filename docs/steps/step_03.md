## STEPS TO RUN locally


### STEP : 1 - Check if the Dockerfile is available in the project directory



### STEP : 2 - Build the Docker image

``` bash
docker build --build-arg AWS_ACCESS_KEY_ID=<AWS_ACCESS_KEY_ID> --build-arg AWS_SECRET_ACCESS_KEY=<AWS_SECRET_ACCESS_KEY> --build-arg AWS_DEFAULT_REGION=<AWS_DEFAULT_REGION> --build-arg MONGODB_URL=<MONGODB_URL> . 
```


### STEP : 3 - Run the Docker image
```bash
docker run -d -p 8080:8080 <IMAGE_NAME>
```