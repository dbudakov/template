# -*- mode: ruby -*-
# vi: set ft=ruby:
Vagrant.configure("2") do |congig|
        congig.vm.define "os" do |os|
                os.vm.box = ""
                os.vm.host_name = ""
                os.vm.network  "", ip: ''
                os.vm.provider :virtualbox do |vb|
                        vb.customize ["modifyvm", :id, "memory", "256"]
                end
                os.vm.provision "shell", inline: <<SHELL
SHELL
        end
end
