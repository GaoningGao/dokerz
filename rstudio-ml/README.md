### For building in a new folder with a Dockerfile in it (you can add your packages to it)

docker build --rm -t 42n4/rstudio-ml .

### Run bash in a docker

docker run -it 42n4/rstudio-ml /bin/bash
