# Installation

## Ubuntu
sudo apt-add-repository -y ppa:ansible/ansible
sudo apt-get update -y
sudo apt-get install -y curl git software-properties-common ansible


## Arch
sudo pacman -Syu
sudo pacman -S curl git ansible

# Run
ansible-playbook lain.yml --ask-vault-pass

# Post
ansible-pull -U git@github.com:trynn-tech/dotfiles.git
