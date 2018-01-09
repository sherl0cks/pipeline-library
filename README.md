# What This Repo Is

A repository of application centric [Jenkins pipeline files](https://jenkins.io/doc/book/pipeline/) that can be referenced or reused for appropriate applications.
We'll organize pipelines by the build tool of application. 

It will be common to require custom Jenkins slaves, and if so, a README should link to a slave definition.

# What This Repo Is NOT 

* steps / functions / library code 
* end to end examples/demos/quickstarts. 
* infrastructure / platform centric Jenkinsfile

Please see https://github.com/redhat-cop/container-pipelines or https://github.com/redhat-cop/containers-quickstarts for this type of content.

## Helpful Hints

* [IDE Syntax Support](https://gist.github.com/arehmandev/736daba40a3e1ef1fbe939c6674d7da8). Each GDSL syntax file will be specific to the plugins you have installed, so please don't commit the resulting file. There


# Other Resources

* https://github.com/fabric8io/fabric8-jenkinsfile-library which influenced the structure of this project