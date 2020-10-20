## Vagrantfiles 


## Set up the vagrant environment with QEMU/KVM provider

### Install the QEMU/KVM 

```
sudo dnf install -y qemu-kvm libvirt libguestfs-tools virt-install rsync virt-manager
```

### Enable the libvirt daemon

```
sudo systemctl enable --now libvirtd
```

### Install the vagrant 

``` 
sudo dnf install -y vagrant
```

### Install the vagrant plugin for Libvirt

```
sudo vagrant plugin install vagrant-libvirt
```
