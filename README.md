# singularity
Work done with singularity containers

## To build a container issue the following:

```bash
singularity build <container-name> <container-build-file>
```

Create writable singularity folder

```bash
singularity build --sandbox <container-folder> <container-build-file>
```

Run container folder writable

```bash
singularity run --writable <container-folder>
```

## To run a container issue one of the following

```bash
chmod 755 <container-name>
./<container-name>
```

