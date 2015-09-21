# -*- mode: ruby -*-

# vi: set ft=ruby :
 
VAGRANTFILE_API_VERSION = "2"
 
Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

		config.vm.hostname = "centos6.hacklab"
		config.vm.box = "gutocarvalho/centos6x64"

		config.vm.provider "virtualbox" do |virtualbox|
			virtualbox.customize [ "modifyvm", :id, "--cpus", "1" ]
			virtualbox.customize [ "modifyvm", :id, "--memory", "300" ]
	end
end
