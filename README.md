# Experimenting with `mojo`

See: https://docs.modular.com/mojo/manual/get-started

For this experiment, I just used the pixi package manager that they recommended. See other repo where I experimented.

Some prerequisites: 
```bash
sudo apt-get update
sudo apt-get install build-essential    # Required for mojo to build
# Otherwise building will fail with: /usr/bin/ld: cannot find Scrt1.o: No such file or directory 
```

I ran `mojo hello_world.mojo` which behaves similar to python and performs just-in-time compilation.

I can compile it into an executable with `mojo build hello_world.mojo`.
