# docker-pipeline-yml-plugin

This project is a jenkins plugin to run [https://github.com/Dockins/docker-pipeline](docker-pipeline.yml) builds inside jenkins as a 
[https://jenkins.io/pipeline/getting-started-pipelines/](pipeline). 
The jenkins runner is a distinct piece of code, actually converting the yml description into pipeline's groovy CPS and relying on 
[https://github.com/Dockins/docker-slaves-plugin](docker-slaves) to run stages. Doing so it benefit Jenkins Pipeline infrastructure, 
visualization and integration in [https://jenkins.io/projects/blueocean/](blueocean) new generation web UI.
