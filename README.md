# Como Instalar Beef en  Kali Linux

Te voy a enseñar como instalar BeeF, es una herramienta que te permite optener infiormacion de la victima por medio de una URL

## Actualizacion 

### PASO 1
> Vamos abrir una terminal y vamos  poner el siguiente comando
```
sudo apt-get update
```
### PASO 2
> Vamos a poner el siguiente comando
```
sudo apt-get upgrade
```
### PASO 3
> Vamos a poner el siguiente comando para estar en modo ROOT y de esta manera instalar Beef
```
sudo su
```
---------------------------
## Instalacion de Beef

### PASO 1
> Vamos abrir una terminal y vamos  poner el siguiente comando
```
git clone https://github.com/beefproject/beef.git
```
### PASO 2
> Vamos a ingresar a la carpeta Beef
```
cd beef
```
### PASO 3
> Vamos a instalar Beef
```
./install
```
### PASO 3
> Vamos a poner el siguiente comando para modificar 'config.yaml'
```
namo config.yaml
```
> Vamos a modificar el password del archivo 'config.yaml'
```
passwd = 12345
```
### PASO 3
> Vamos a ejecutar Beef
```
./beef
```
