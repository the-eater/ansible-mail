
Vagrant.configure("2") do |config|

  config.vm.box = "boxcutter/ubuntu1604"

  config.vm.provision "shell", inline: <<-SHELL
    apt-get install -y software-properties-common
    apt-add-repository -y ppa:ansible/ansible
    apt-get update
    apt-get install -y ansible
  SHELL
end
