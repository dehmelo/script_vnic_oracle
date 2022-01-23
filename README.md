# Script Configure Secondary VNIC Oracle Cloud

### Instale o git:
```dnf install -y git```

```apt install -y git```

### Faça o clone do repositório:
```git clone https://github.com/dehmelo/script_vnic_oracle.git```

### Entre no repositório clonado:
```cd script_vnic_oracle/```

### Mude as permissões do arquivo para que possa ser executado:
```chmod +x secondary_vnic_all_configure.sh```

### E execute o script com a flag '-c':
```./secondary_vnic_all_configure.sh -c```

### Caso tenha executado sem a flag '-c', note que ao rodar o scrit apareceu uma tabelinha com algumas configurações definidas pela execução do script, faça a copia deste ip que foi atribuido a interface ens5 e execute:
```ifconfig ens5 ip-que-foi-copiado netmask 255.255.255.0```


