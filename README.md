# docker-r-h2o

## News

Update to R version 3.6.2

## Description

Image template to run any R program/script in the container

Learn to understand this repository using this course https://www.udemy.com/docker-containers-data-science-reproducible-research/?couponCode=DOCKERRR

## Details

-- started from rocker/r-base
-- including java
-- added several packages including h2o

## Usage

### Pull container

`docker pull vladdsm/docker-r-h2o`

### Run container using folder mapping

`docker run --rm -it -v /Users/vladdsm/Shared:/03_output vladdsm/docker-r-h2o`

### Access running container from another terminal

`docker exec -it [container ID] bash`

