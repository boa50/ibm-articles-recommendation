# IBM Articles Recommendation

This project tries to present recommendations about articles at the IBM Watson Studio platform.

## Installation

You can run the project using Docker containers.

There are Dockerfiles inside the container folder.

There are example commands at the file notebooks\_container\_start.sh.sample, that shows how to run the container.

There is a requiriments.txt file toghether with the Dockerfile, if you want to run the code a different way.

## Dataset

The dataset is based on 2 files articles\_community.csv and user-item-interactions.csv.

articles\_community.csv file contains data about the content of the articles.

user-item-interactions.csv file shows information about how users interacted with the articles.

## Project Organization

Recommendations\_with\_IBM.ipynb is the main jupyter notebook used to analyze the data and make recommendations.

The container folder contains the Dockerfile and the requirements.txt used to build the Docker container to run the project.

The dataset folder contains the .csv files used to analyze the data.

The extra has files used to validate some steps inside the notebook based on files supplied by Udacity.

## Acknowledgments

- IBM for supplying the dataset to use in the project.

- Udacity for supplying the project idea and the jupyter notebook template.
