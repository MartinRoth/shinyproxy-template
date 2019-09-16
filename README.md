
# ShinyProxy Template

This repository provides a template to deploy your own Shiny apps on [ShinyProxy](https://www.shinyproxy.io).

Full explanation on the contents of this repository is offered at

https://www.shinyproxy.io/deploying-apps/

The purpose of this repository is to customize it for your needs, but if you want to build a Docker image from the Dockerfile in this repository, navigate into the root directory of this repository and run

```
sudo docker build -t openanalytics/shinyproxy-template .
```

Running the image for testing purposes outside ShinyProxy can be done using e.g.

```
sudo docker run -it -p 3838:3838 openanalytics/shinyproxy-template
```

Test Martin 2
Test Martin 3 - 4
Test Martin 5

(c) Copyright Open Analytics NV, 2016-2018.
