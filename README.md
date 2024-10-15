# ✅ Definição de um cluster Swarm local com Vagrant
- ⁠Criar um Vagrantfile com as definições de 4 máquinas virtuais. Sendo uma máquina com o nome de master e as outras com os nomes de node01, node02 e node03;
- Cada máquina virtual deverá ter um ip fixo;
- Todas as MV deverão possuir o Docker pré-instalado;
- ⁠A máquina com o nome de master deverá ser o nó manager do cluster.
- As demais máquinas deverão ser incluídas no cluster swarm como workers.
### Instalar o Kubectl
Instalação - [Site Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/)

    curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/darwin/amd64/kubectl"
   
