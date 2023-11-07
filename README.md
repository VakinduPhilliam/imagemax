
# Image Max:

Image Max is an AI powered web app that uses Machine Learning to determine the most relevant Bitbucket project pull-requests that require the software developer's  urgent attention while filtering out less important pull-requests. 

Individually reviewing a large software project's pull requests, issues and active alerts can be hectic for any software developer. 

Image Max uses a pretrained Machine Learning model that is fine-tuned to identify genuine in-progress Bitbucket project pull requests, while filtering out less important pull-requests, profanity and abuse. 

The Image Max container image is hosted on Docker hub and uses Scikit-Learn and Pandas to build a Machine Learning Profanity Detection Model that also filters out less important pull-requests. 

The app then plots a graph to notify the developer about the most critical project pull-requests that are worth the developer's time. 

For example 'README.md' documentation updates are ignored by the model, because they aren't critical updates.

<br/>

_Image Max Interface:_

![Imagemax of Work Interface 1](/docs/ui1.png)

</br>

![Imagemax of Work Interface 2](/docs/ui2.png)

</br>

![Imagemax of Work Interface 3](/docs/ui3.png)

</br>

![Imagemax of Work Interface 4](/docs/ui4.png)

</br>

## Machine Learning Technologies Used:

- Python3 - programming language used for Machine Learning.

- Pandas - is used for data cleaning and analysis.

- Scikit-learn (SKlearn) - is used for Machine Learning and Statistical Modeling.

- Pip8 or greater - is used for managing python dependency installations.

- Docker Hub - Used to build container Image.

<br/>

## Installation on Desktop PC:

Install the following applications on your PC before running the web app.

- [Node.JS](https://nodejs.org/en/download/current/)

- [Docker](https://docs.docker.com/get-docker/)

</br>

APP's DOCKER CONTAINER IMAGE URL: https://hub.docker.com/repository/docker/vakinduphilliam/imagemax/general

</br>

Pull and run the container image from Docker Hub.

In your command terminal, pull the image from Docker Hub by running the command below.

_docker pull vakinduphilliam/imagemax:tagname_

</br>

To run the container image locally, run the command below.

_docker run vakinduphilliam/imagemax:tagname_

</br>

## LIVE DEMO URL:

Visit the URLs below to see working demos.

LIVE WEB APP: https://imagemax.myeulome.com


