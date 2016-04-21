Provision a Mac for Development using Ansible
=============================================

Provision a machine running Mac OS X for development using [Ansible](https://www.ansible.com).


Features
--------

- Xcode developer tools install
- Osxlockdown (* Requires OS X 10.11 El Capitan)
- Python pip install
- Python virtualenv/virtualenv-wrapper install
- Dotfiles for OS X
- Homebrew Bundle file creation
- Homebrew install
- Homebrew applications
- Homebrew Cask install
- Homebrew Cask applications
- Mackup restore
- Mackup backup
- Zsh configuration
- Prezto configuration


Roles
-----

- General
- Osxlockdown
- Python
- Ruby
- Node
- Homebrew
- Dotfiles
- Git
- Mackup
- Sublime Text
- Zsh
- Prezto


Usage
-----

Running locally:
```
$ ansible-playbook -i inventories/macbook -c local --ask-pass --ask-sudo-pass main.yml
```

Running remotely:
```
$ ansible-playbook -i inventories/macbook --ask-pass --ask-sudo-pass main.yml
```


Author
------

Peter Schaadt

[https://github.com/peterfschaadt](https://github.com/peterfschaadt)

[http://peterschaadt.com](http://peterschaadt.com)
