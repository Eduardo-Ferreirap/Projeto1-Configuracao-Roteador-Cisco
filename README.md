# Projeto 1 - Configuração Roteador Cisco
Este projeto tem como objetivo demonstrar a configuração básica de um roteador Cisco utilizando o simulador Cisco Packet Tracer, feito durante o curso técnico em Redes de Computadores.

# Objetivos de Aprendizado
Compreender a estrutura de configuração de um roteador Cisco.

Aplicar comandos básicos na CLI (Command Line Interface).

Realizar o endereçamento IP e testar a conectividade da rede.

Garantir segurança de acesso com senhas.

# Tecnologias e Ferramentas
💻 Cisco Packet Tracer (versão XX – substitua pela versão que você usou)

🛠️ Equipamentos simulados: Roteador Cisco, Switch, PC

🧾 Cisco IOS Commands (Interface de Linha de Comando da Cisco)

# Funcionalidades Configuradas
✅ Nome do dispositivo (hostname)

✅ Configuração de senhas:

Console (line console 0)

Acesso remoto (line vty 0 4)

Privilegiado (enable secret)

✅ Configuração de interfaces:

IPs estáticos nas interfaces FastEthernet ou Serial

Ativação de interfaces com no shutdown

✅ Criação de banners de aviso

✅ Salvamento da configuração com copy running-config startup-config

✅ Teste de conectividade com ping e show ip interface brief

# Estrutura de Arquivos
lua
Copiar
Editar
📁 Projeto1_Config_Roteador_Cisco/
├── README.md                ← Este arquivo com descrição do projeto
├── Projeto1.pkt             ← Arquivo do Packet Tracer com a topologia simulada
└── comandos_utilizados.txt  ← Arquivo com os principais comandos Cisco usados no projeto
