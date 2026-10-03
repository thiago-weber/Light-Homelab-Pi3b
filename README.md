# Light Homelab Pi3b
Repositório de Homelab leve para Raspberry Pi 3B+

Este é um repositório leve montado com docker, utilizando serviços essenciais como Pi-hole, Tailscale, Portainer, Glances, Syncthing e organização de Homepage.

![](https://img.shields.io/badge/hardware-raspberry_pi_3b%2B-brightgreen?logo=raspberrypi)
![](https://img.shields.io/badge/OS-debian_GNU_linux_13-brightgreen?logo=gnu)
![](https://img.shields.io/badge/engine-docker-brightgreen?logo=docker)
![](https://img.shields.io/badge/license-MIT-brightgreen)

## Índice
• Especificações de Hardware e Sistema
• Arquitetura e Serviços
• Estrutura de Pastas
• Instalação
• Fontes
• Licença

## Especificações de Hardware e Sistema
Para esse Homelab, foi utilizado:
• Raspberry Pi 3B+
• Cartão MicroSD de 32gb
• Debian Linux 13

## Arquitetura e Serviços
Os seguintes serviços foram utilizados:
• Homepage: Dashboard para organização e monitoramento dos serviços localmente, usando a porta 3000.
• Pi-hole: Bloqueador de anúncios e rastreadores em nível de rede, usando as portas 53 e 80.
• Tailscale: Rede privada VPN para acesso remoto.
• Syncthing: Sincronização contínua de arquivos e notas entre dispositivos e servidor, usando a porta 8384.
• Portainer: Interface web para gerenciamento de containers, imagens e volumes do Docker, usando a porta 9000;
• Glances: Monitor de recursos do sistema, usando a porta 61208.
