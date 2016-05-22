Vagrant.configure(2) do |config|
 config.vm.box = "ubuntu/trusty64"
 config.vm.hostname = "robbroeckxs"
 config.vm.network "forwarded_port", guest: 81, host: 8181
 config.vm.provision "shell", path: "provision_apache.sh"
 config.vm.provision "shell", path: "provision_php.sh"
 config.vm.provision "shell", path: "provision_gitclone.sh"
end