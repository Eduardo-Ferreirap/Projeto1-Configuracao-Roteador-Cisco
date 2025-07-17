# Projeto 1 – Configuração de Roteador Cisco
Este projeto demonstra a configuração básica de um roteador Cisco utilizando o Cisco Packet Tracer. Foi desenvolvido como parte do curso técnico em Redes de Computadores para consolidar conceitos fundamentais de configuração e gerenciamento de dispositivos de rede.

# Objetivos do Projeto
- Configurar endereçamento IP em interfaces.
- Definir senhas criptografadas para acesso seguro.
- Configurar banner de aviso para segurança.
- Ativar e configurar interfaces Ethernet.
- Salvar a configuração para inicialização automática.

# Necessário:
- Cisco Packet Tracer
- 1 Roteador e 1 PC


# Configurações
- Hostname

nginx
Copiar
Editar
hostname Roteador
Criptografia de senhas

nginx
Copiar
Editar
service password-encryption
Senha do modo privilegiado

bash
Copiar
Editar
enable secret <senha criptografada>
Senha para acesso remoto (VTY)

pgsql
Copiar
Editar
line vty 0 4
 password <senha criptografada>
 login
Banner de aviso

nginx
Copiar
Editar
banner motd ^C SOMENTE AUTORIZADOS ^C
Configuração de Interfaces

kotlin
Copiar
Editar
interface GigabitEthernet0/0
 description interface conectada ao roteador de borda
 ip address 192.168.10.1 255.255.255.0
 no shutdown


