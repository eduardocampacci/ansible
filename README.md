# Ansible

Repositório com playbooks, módulos e arquivos utilizados para automação e administração de ambientes Linux e Windows.

## Estrutura

| Pasta | Descrição |
|---|---|
| `arquivos/` | Arquivos utilizados pelos playbooks |
| `group_vars/` | Variáveis compartilhadas |
| `hosts` | Inventário Ansible |
| `modulos/` | Módulos, exemplos e arquivos auxiliares |
| `playbooks/linux/` | Playbooks para servidores e clientes Linux |
| `playbooks/windows/` | Playbooks para ambientes Windows |

## Playbooks Linux

| Playbook | Descrição |
|---|---|
| `cli_debian12.yml` | Configuração de estações Debian |
| `srv_debian12.yml` | Configuração base de servidores Debian |
| `hw_srv_debian12.yml` | Configuração padrão servidores Hewitt |
| `hw_bacula_update.yml` | Atualização de ambiente Bacula |
| `hw_bkp_configs.yml` | Backup de arquivos de configuração |
| `hw_samba4_update.yml` | Atualização de servidores Samba4 |
| `home_xfce.yml` | Configuração ambiente XFCE |

## Playbooks Windows

| Playbook | Descrição |
|---|---|
| `ingressar_dominio_rede.yml` | Ingressar máquina no domínio |
| `reset_senha_admin_local.yml` | Reset senha administrador local |
| `setar_dns_ip_fixo.yml` | Configuração DNS/IP fixo |
| `setar_dns_ip_dhcp.yml` | Configuração DHCP |
| `install_programs_chocolatey.yml` | Instalação programas via Chocolatey |
| `install_programs_exe.yml` | Instalação programas EXE |
| `install_sicalc.yml` | Instalação Sicalc |
| `copia_pasta_windows.yml` | Cópia de arquivos/pastas |
| `criacao_arquivo_windows.yml` | Criação de arquivos no Windows |

## Observações

- Ajuste hosts, IPs e variáveis antes de executar.
- Alguns playbooks precisam de privilégios administrativos.
- Ambiente utilizado para laboratório e produção.
