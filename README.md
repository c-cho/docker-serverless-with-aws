# docker-serverless-with-aws
This is a dockerfile used for circleci 2.0.  

![I-Love-CircleCI](https://circleci.com/blog/media/1107-Picard%20Blog-Docker-06.png)

## Inside it
- Ubuntu 16.04
- openjdk-8-jdk
- nodejs 6
- python 3.6
- serverless framework
- Japanese environment

## Use it
### For CircleCI 2.0
```yaml
version: 2
jobs:
  build:
    # ...
    docker:
      - image: choasia/serverless-with-aws
    # ...
```
### For other usages
`docker pull choasia/serverless-with-aws` **OR** [Docker Hub](https://hub.docker.com/r/choasia/serverless-with-aws/)

## License
Apache 2.0
