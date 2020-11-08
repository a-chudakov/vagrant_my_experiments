# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.vm.define "ubuntu" do |subconfig|
    subconfig.vm.box = "ubuntu/focal64"
  end

  config.vm.define "centos" do |subconfig|
    subconfig.vm.box = "centos/8"
  end
end
