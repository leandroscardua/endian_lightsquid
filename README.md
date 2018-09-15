Endian Lightsquid
=============
Addon for Endian Firewall 3.2, This tool allows to use Lightsquid , it's possible enable and disable the addon for Web interface / 
Addon para Endian Firewall 3.2, esse addons permite usar o Lightsquid, é possivel habilitar e desabilitar o addons pela Interface web.

Version/Versão:
--------
v.1

Requirements/Requerimento:
--------
Download : lightsquid-endian3-2.0-1.x86_64.rpm


Installation/Instalação:
--------
    curl -Lo lightsquid-endian3-2.0-1.x86_64.rpm https://github.com/leandroscardua/endian_lightsquid/blob/master/lightsquid-endian3-2.0-1.x86_64.rpm?raw=true
    rpm -Uvh lightsquid-endian3-2.0-1.x86_64.rpm 
    
    
Configuration/Configuração:
--------
For web interface, Click on the tab Reports and Logs --> Proxy --> HTTP Report
Click on Active Lightsquid --> Save 

/

Pela interface web, clique na aba registros e relatorios --> Proxy --> Relatorio HTTP
Clica em Ativar Lightsquid --> Guardar

Definindo uma senha para o usuario lighsquid:

    Execute o script no console ssh: /usr/local/bin/lightsquid-password.sh ou lightsquid-password.sh.
    Digite a senha a ser utilizada para acessar os relatorios e pressione ENTER.

Acesso direto aos relatorios:

Link: https://YOURENDIANGREENIP:10443/lightsquid (Ex: https://192.168.0.15:10443/lightsquid )

Logue com o usuario lightsquid e forneça a senha configurada no passo anterior (scripts de senha).

Credits/Creditos:  
--------

An addon by Bruno Almeida - Linkedin:https://github.com/brunoalmeida33/EndianFirewall3.2_Lightsquid

/

addons feito por Bruno Almeida - Linledin: https://www.linkedin.com/in/bruno-almeida-de-oliveira-39336913b





