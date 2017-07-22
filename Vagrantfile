# vi: set ft=ruby :
 
Vagrant.configure("2") do |config|
    config.vm.box = "bento/ubuntu-17.04"
    config.vm.synced_folder ENV['HOME'], "/myhome", type: "nfs"

    config.vm.provider "vmware_fusion" do |v|
      v.memory = 4096
      v.cpus = 1
    end
 
    config.vm.define "tcmaster01" do |node|
      node.vm.hostname = "tcmaster01"
      node.vm.network "private_network", type: "dhcp"

      # Use NFS for shared folders for better performance
      node.vm.synced_folder '.', '/vagrant', nfs: true
    end 
end
