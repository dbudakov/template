# -*- mode: ruby -*-
# vi: set ft=ruby:
Vagrant.configure("2") do |config|
	config.vm.define "os" do |os|
		os.vm.box = ""
		os.vm.host_name = ""
		os.vm.network  "", ip: ''
		os.vm.provider :virtualbox do |vb|
			vb.name = ""
			vb.customize ["modifyvm", :id, "--memory", "256"]
		end
		os.vm.provision "shell", inline: <<SHELL
SHELL
	end
## Устанавливаем связь между каталогом "./src" хост-системы
## и каталогом "/home/vagrant" гостевой системы.
#		config.vm.synced_folder "./src", "/home/vagrant"
end

