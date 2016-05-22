Vagrant.configure(2) do |config|
 config.vm.box = "ubuntu/trusty64 --minimal"
 config.vm.hostname = "robbroeckxs"
 config.vm.network "forwarded_port", guest: 80, host: 8080
end