### Singularity container definition for MSFragger 2.4

This container definition assumes that you have the [MSFragger](http://msfragger.nesvilab.org/)
software (`MSFragger-2.4.zip`). It then builds a container and installs the `msfragger`
shell script so that you can run MSFragger with:

```
singularity exec container.simg msfragger opts
```

where `container.simg` is the path to the container and `opts` are the MSFragger command line options.
