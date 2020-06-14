# ruby-in-jupyter
Using Ruby in Binder via repo2docker

## To run in a web interface
https://mybinder.org/v2/gh/yoomlam/ruby-in-jupyter/master?filepath=ruby_notebook/ruby1.ipynb

## To run locally
```
docker run -p 8888:8888 -v `pwd`:/home/jovyan/on_host rubydata/datascience-notebook
```
See https://github.com/SciRuby/iruby#docker

### Alternative setup using Dockerfile
Not recommended for use with mybinder.org, but a good resource in case we want a container.
See https://github.com/RubyData/docker-stacks/blob/master/binder/Dockerfile

