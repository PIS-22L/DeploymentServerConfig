# Deploying backend app instructions

- download backend app (.jar) image from nexus

``` curl -L <artifact_url> --output backend.jar ```

- start docker daemon (if not already running)

- build and run docker image at port 8082 (detached mode):

``` docker-compose up -d ```


## Stop server

``` docker-compose down ```
