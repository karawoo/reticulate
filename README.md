
## TensorFlow for R

[TensorFlow™](https://tensorflow.org) is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API. 

The tensorflow R package provides access to the complete TensorFlow API from within R.

## Installation

1. Install the main TensorFlow distribution:

  https://www.tensorflow.org/get_started/os_setup.html#download-and-setup

2. Install the tensorflow R package:

    ```r
    library(devtools)
    install_github("rstudio/tensorflow", auth_token = "b3ed53b2a3f239d1a994ee7193139b4a79daaf8c")
    ```

## Documentation

The documentation for the tensorflow package will be published using gh-pages once this repository is public. For the time being you can access a copy of the documentation installed along with the package by calling the `view_docs` function: 

```r
tensorflow:::view_docs()
```



