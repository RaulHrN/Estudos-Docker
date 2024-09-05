
# Comandos do Docker

Listagem dos comandos principais e comando genéricos do Docker

## Comandos mais usados

| Comando | Descrição |
| - | - |
| `--version` | exibir a versão do Docker |
| `build -t <nome_da_imagem> .` | construir uma imagem a partir de um Dockfile |
| `exec -it <container_id> <comando>` | executar comandos dentro de um container |
| `images` | listar todas as imagens no ambiente local |
| `inspect <container_id` | exibir detalhes sobre um container |
| `logs <container_id>` | ver logs de um container |
| `network create <nome_da_network>` | criar uma network |
| `network ls` | listar redes no ambiente local |
| `ps` | listar containers em execução |
| `ps -a` | listar todos os containers |
| `pull <imagem>` | baixar uma imagem do Docker Hub |
| `rm <container_id>` | remover um container |
| `rmi <imagem>` | remover uma imagem |
| `run -d -p <host_port>:<container_port> <imagem>` | criar e iniciar um container |
| `start <container_id>` | iniciar um container parado |
| `stats` | monitorar uso de recursos pelos containers |
| `stop <container_id>` | parar um container |
| `system prune` | remover imagens, containers e volumes não utilizados |
| `volume ls` | listar volumes no ambiente local |

## Outros comandos
| Comando | Descrição |
| - | - |
| `commit <container_id> <nova_imagem>` | comitar mudanças de um container em uma nova imagem |
| `cp <container_id>:<caminho_no_container> <caminho_no_host>` | copiar arquivos de um container |
| `history <imagem>` | listar histórico de uma imagem |
| `inspect -f '{{ .State.Running }}' <container_id>` | vver tempo de execução de um container |
| `pause <container_id>` | pausar todos os processos dentro um container |
| `push <usuario>/<nome_da_imagem>` | subir uma imagem para o Docker Hub |
| `restart <container_id>` | Restartar um container |
| `rename <nome_atual> <novo_nome>` | renomear um container |
| `rm $(docker ps -a -q)` | remover todos os containers parados |
| `rmi $(docker images -q)` | remover todas as imagens |
| `stop $(docker ps -q)` | parar todos os containers em execução |
| `top <container_id>` | listar os processos em execução em um container |
| `unpause <container_id>` | despausar um container |
| `volume create <nome_do_volume>` | criar um volume |
| `volume prune` | limpar volumes não utilizados |
| `* systemctl restart docker` | reiniciar serviço Docker |
| `* systemctl status docker` | verificar status do Docker |
