# Entrega continua

###### Comandos do vagrant
```
vagrant init hashicorp/precise64
vagrant up
vagrant ssh
vagrant halt - para parar
```

###### Comandos do vagrant relacionado ao ssh
```
ssh-keygen -t rsa
vagrant ssh
ls /vagrant
cp /vagrant/id_bionic.pub .
cat id_bionic.pub >> .ssh/authorized_keys
ssh -i sua_chave_privada vagrant@seu-ip
```

###### Comando para subir uma maquina especifica dentro do vagrant

```
vagrant up nome da maquina
```

