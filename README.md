# Atenção: Instale o Guacamole Server e configure a máquina onde será instalado o thunderbird para acesso remoto via RDP
Acesse: https://github.com/davigalucio/guacamole-server/ 

1. Instale o Guacamole Server no linux Debian 12:

apt install -y git

git clone https://github.com/davigalucio/guacamole-server.git

sh guacamole-server/INSTALL.SH


3. Instale o Thunderbird para acesso via RDP web com o Guacamole Server

apt install -y git

git clone https://github.com/davigalucio/web-thunderbird-no-linux-debian12.git

sh web-thunderbird-no-linux-debian12/INSTALL.SH
