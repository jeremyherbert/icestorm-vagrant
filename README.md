To use this, simply clone the repository and run `vagrant up`:

```
git clone https://github.com/jeremyherbert/icestorm-vagrant
cd icestorm-vagrant
vagrant up
```

This will install the latest versions of icestorm, arachne-pnr and yosys. To access the machine, run:

`vagrant ssh`

You can share files with the host machine using the directory you ran the vagrant commands it. It will be mounted in the virtual machine at `/vagrant/`.

The Lattice development kits using FTDI interface chips should automatically be connected to the virtual machine.
