### Protocolo de rede

-   TCP/IP - É um protocolo que conecta as redes LAN ou WLAN
- É Dividido por camadas
    -   Físico
    -   Enlace
    -   Rede    > è o IP de origirem e destino
    -   Transporte  > TCP
    -   Sessão      > 
    -   Apresentação
    -   Aplicação

### Comandos 

    -   ss ou ss -lt    Lista as portas abertas
    -   ip route    Verificar minhas rotas
    -   ip -s link     Para verificar o status do link da rede se está "UP" ou "DOWN"
    -   netplan apply   Para restart na placa de rede
    -   hostname -i     Para saber o IP do meu host
    -   hostname -f     Para saber o nome atual do host
    -   hostname -d     Para saber se temos algum tipo de domínio
    -   traceroute      Para ver as rotas trançadas
    -   netstat -nr ou route -n     Para verificar o roteamento de rede

    -   Listando todos os serviços
        -   service --status-all

    - Verificando e apagando o cache de update de pacotes
        -   sudo du -sch /var/cache/apt/archives/
        -   sudo apt-get clean --dry-run
### Host e Hostname

    -   Local
        -   /etc/hosts/hosts
