# Hydra-Genetics Vagrant

Build script for a vagrant machine that can be used by Window/OSX user to run snakemake in combination with singularity.

## Build 

### Dependancies

#### Softwares:
- [OSX](https://multipass.run/docs/installing-on-macos)
- [windos](https://multipass.run/docs/installing-on-linux)
- [ubuntu](https://multipass.run/docs/installing-on-windows)

## Run

```bash
#Clone repo
git clone git@github.com:hydra-genetics/multipass.git

# Build machine
cd multipass
multipass launch --cloud-init cloud-init/hydra-genetics.yaml 

# Enter machine
multipass shell {MACHINE_NAME}
```


