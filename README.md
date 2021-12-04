## My project

For my project, I will analyze the `CA_ED_INFO550` data. This repository contains the docker file to build the docker image, and origingal data, R, Rmd and make file to generate the report.

## Execute the analysis

To execute the analysis, you need to:

1. pull the image from the docker hub

``` bash
docker pull jran2/final
```

2. build the image and retrieve the report

First, let's make a directory to store the result, and this folder will be in your root directory

```bash
mkdir ~/docker_output
```

Next, run

``` bash
docker run -v ~/docker_output:/project/output jran2/final
```

Then you can find a `report.html` under the output folder. 

