# Instalação do Redis #

>
O Redis pode ser instalado em diferentes sistemas operacionais. 
>
> 
Serão apresentadas as instruções básicas para instalar o Redis em sistemas Linux e Windows.
>

## Instalação do Redis no Linux ##
>
1. Abra o terminal no seu sistema Linux.
1. Execute o seguinte comando para atualizar os pacotes do sistema:
```
sudo apt update
```
3. Em seguida, execute o seguinte comando para instalar o Redis:
```
sudo apt install redis-server
```
4. O Redis será instalado e executado como um serviço no Linux. Você pode verificar 
o status do serviço usando o seguinte comando:
```
sudo systemctl status redis-server
```
>

## Instalação do Redis no Windows ##
>
1. Acesse o site oficial do Redis (https://redis.io/download) e vá para a seção "Windows" para baixar a versão estável mais recente do Redis para Windows.

1. Após o download, descompacte o arquivo ZIP em uma pasta de sua escolha.

1. Navegue até a pasta em que o Redis foi descompactado e execute o arquivo redis-server.exe.

1. O Redis será iniciado como um servidor no seu computador Windows.
>
