Vagrant.configure("2") do |config|
  config.vm.box = "generic/debian10"
  config.vm.hostname = "??????"
  config.vm.provider "virtualbox" do |v|
    v.name = "m08uf1ex1"
    v.memory = 2048
    v.cpus = 1
    v.customize ['modifyvm', :id, '--clipboard', 'bidirectional']     
  end

  config.vm.network "???????"
       
  config.vm.provision "shell", inline: <<-SHELL
    sudo apt-get update -y
    sudo apt-get install -y net-tools    
  SHELL

end
