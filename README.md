# Packer CentOS 7

Packer config for the boxes which can be found at [https://app.vagrantup.com/russmckendrick/boxes/centos75](https://app.vagrantup.com/russmckendrick/boxes/centos75).

To build both Virtualbox and VMWare boxes run;

```
packer build CentOS_7.json
```

For just VMWare;

```
packer build -only vmware-iso CentOS_7.json
```

And for Virtualbox;

```
packer build -only virtualbox-iso CentOS_7.json
```
