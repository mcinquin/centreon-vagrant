# centreon-vagrant #

## Review ##
### ces3-central-x86_64 ###
Centreon central installed with CES3 (Centreon Enterprise Server) :
* CentOS 6.5 (2vCPU, 4Go RAM, 32Go Drive)
* Centreon 2.5.1
* Centreon Engine 1.3.7
* Centreon Broker 2.6.2
* Centreon Connector 1.0.2
* Centreon CLAPI 1.5.2
* Centreon Syslog Frontend 1.5.2
* Centreon Syslog Server 1.2.5
* Centreon GLPI 1.0.2
* Centreon Plugins


### ces3-poller-x86_64 ###
Centreon poller installed with CES3 (Centreon Enterprise Server) :
* CentOS 6.5 (2vCPU, 4Go RAM, 16Go Drive)
* Centreon Engine 1.3.7
* Centreon Broker 2.6.2
* Centreon Connector 1.0.2
* Centreon Syslog Server 1.2.5
* Centreon Plugins

## Requirements ##

Vagrant, Virtualbox

## Installation ##
1. Download the Centreon Vagrant box :
    * https://www.dropbox.com/s/lo3l98zc27weoju/ces3-central-x86_64.box
    * http://...
2. Download the Vagrantfile and adapt to your box (config.vm.box = "ces3-central-x86_64")
3. Execute following commands (adapt the command to your box) :
```
vagrant add box ces3-central-x86_64 ces3-central-x86_64.box
vagrant up
vagrant ssh
```
