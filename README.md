# time_series_transformer_tf2
A tensorflow 2 transformer nerual network working with time series data.

# To get the docker container already setup 
`docker push docker.pkg.github.com/calumroy/tf2_func_tests/tf2_jupyter_ade:latest`

# To run and enter the docker container
From this directory
`ade start`
`ade enter`
You will then be inside the docker contianer where jupyter and tensorflow2 is already installed with firefox.
Run this to view and interact with the notebooks.
`jupyter notebook`

# Build the ade docker container
`cd ./minial_ade`
`docker build -t tf2_jupyter_ade .`

# Push a new docker image to the repos container repository
`docker push docker.pkg.github.com/calumroy/tf2_func_tests/tf2_jupyter_ade:latest`


# login to github to push new contianers
e.g   
`cat ~/github_tokens/TOKENS.txt | docker login https://docker.pkg.github.com -u calumroy --password-stdin`  

