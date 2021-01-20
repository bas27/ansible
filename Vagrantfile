#VAGRANТFILE_API_VERSION = " 2 "

Vagrant.configure("2") do |config|
    Config.ssh.insert.key = false
    
    config.vm.define "vagrant1" do |vagrant1|
        config.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.33.10"
        config.vm.network "public_network"
        config.vm.network "forwarded_port", guest: 80, host: 8080
        config.vm.network "forwarded_port", guest: 443, host: 8443
    end

    config.vm.define "vagrant1" do |vagrant2|
        config.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.33.11"
        config.vm.network "public_network"
        config.vm.network "forwarded_port", guest: 80, host: 8081
        config.vm.network "forwarded_port", guest: 443, host: 8444
    end

    config.vm.define "vagrant1" do |vagrant3|
        config.vm.box = "ubuntu/trusty64"
        config.vm.network "private_network", ip: "192.168.33.12"
        config.vm.network "public_network"
        config.vm.network "forwarded_port", guest: 80, host: 8082
        config.vm.network "forwarded_port", guest: 443, host: 8445
    end

end