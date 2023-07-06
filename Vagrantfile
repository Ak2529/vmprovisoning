Vagrant.configure("2") do |config|

  config.vm.define "scriptbox" do |scriptbox|
    scriptbox.vm.box = "geerlingguy/centos7"
        scriptbox.vm.network "private_network", ip: "192.168.10.12"
        scriptbox.vm.hostname = "scriptbox"
        scriptbox.vm.provider "virtualbox" do |vb|
     vb.memory = "1024"
   end
  end

