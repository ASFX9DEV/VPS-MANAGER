
__ASFX9DEV 1.0__

__Recomendado__
- Ubuntu 18

![logo](https://github.com/ASFX9DEV/VPS/blob/main/home.png)

__Instalar apenas o SCRIPT__

```
wget https://raw.githubusercontent.com/ASFX9DEV/VPS/main/Plus; chmod 777 Plus;./Plus
```

__Instalar o SCRIPT e atualizar pacotes do sistema__

```
apt-get update -y; apt-get upgrade -y; wget https://raw.githubusercontent.com/ASFX9DEV/VPS/main/Plus; chmod 777 Plus;./Plus
```

__Alterar senha Root__

```
sudo -i
```

```
bash <(wget -qO- https://raw.githubusercontent.com/ASFX9DEV/VPS/main/senharoot.sh)
```