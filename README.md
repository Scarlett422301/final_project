## My project

For my project, I will analyze the `CA_ED_INFO550` data.

To analyze the data you will need to download this folder. 

## Execute the analysis

To execute the analysis, from the project folder you can run 

``` bash
docker build -t final .
docker run -v ~/Downloads/final_project-main/output:/project/output final
```

Then you can find a `report.html` under the output folder. Note that you may need to change the `~/Downloads/final_project/output`, and this depends on where you store this downloaded folder.

## pull from the docker hub
