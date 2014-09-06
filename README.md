ubuntuEnvSettings
=================
1. ZSH settings
$ sudo apt-get -y install zsh
$ git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
$ chsh %s -s /bin/zsh  # %s is your login user name, you can use this command to confirm it-> $ whoami
$ git clone https://github.com/AaronZhangL/ubuntuEnvSettings.git
$ cp ${ubuntuEnvSettings}/conf/zshrc ~/.zshrc # ${ubuntuEnvSettings} is the root folder of git cloned. 
# reboot you os.
