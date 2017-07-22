# tc-vmware-ubuntu-zestyzapus64-17.04-rocksdb

Ubuntu 17.04 Vagrant WMVare Development machine for RocksDB development with Golang.

## Getting started

```bash
cd $HOME/Desktop
git clone https://github.com/topconnector/tc-vmware-ubuntu-zestyzapus64-17.04-rocksdb.git
cd tc-vmware-ubuntu-zestyzapus64-17.04-rocksdb
```

You must have the following installed:

* VMware Fusion (Pro) >= 8.5
  
  https://www.vmware.com/products/fusion/fusion-evaluation.html
    
* Vagrant >= 1.9.7

  Download and install from https://www.vagrantup.com/.

  Vagrant + VMware
  
  Download and install from https://www.vagrantup.com/vmware/index.html
     
* update VMWare box

  Install by running: 
    
```bash
   vagrant box add bento/ubuntu-17.04
```
    
* run Virtual machine (VM)

  Install by running: 
  
```bash
    vagrant up --provider vmware_fusion
```
