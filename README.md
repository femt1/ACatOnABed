# A Cat On A Bed
Repository containing select data from experiments in Cat on a Bed: Control-Theoretic Techniques for Reducing GC Interference

The repo is organised as follows:
* Raw data (in folder initial-files)
* Averaged raw data files in csv format
* Graphs
* Kubernetes configuration files (in Kubernetes folder)

Repository containing code for the different modes are provided at https://github.com/femt1/520-ElasticGC
The repository also contains a copy of the OpenJ9 JVM used to develop the code i.e. the code relating to this project have been integrated into this copy of the OpenJ9 JVM. The JVM must then be built to be usable as a test JVM (use the command `make all`). For the build to be successful,all required aspects specified in OpenJ9 documentation must be present(see https://github.com/eclipse/openj9/blob/master/doc/build-instructions/Build_Instructions_V11.md). 


