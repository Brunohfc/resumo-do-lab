# Passo a Passo para Criar uma Instância de Máquina Virtual na Azure

## Pré-requisitos
- Conta ativa na Microsoft Azure
- Acesso ao portal Azure

### Passo 1: Acessar o Portal Azure
1. **Login**: Entre no [Portal Azure](https://portal.azure.com) usando suas credenciais.

### Passo 2: Criar a Máquina Virtual
1. **Navegue para "Máquinas Virtuais"**:
   - No menu lateral esquerdo, clique em "Máquinas Virtuais".
   - Clique em "+ Criar" e selecione "Máquina Virtual".

2. **Configurações Básicas**:
   - **Assinatura**: Escolha a assinatura da Azure que você deseja usar.
   - **Grupo de Recursos**: Selecione um grupo de recursos existente ou crie um novo.
   - **Nome da Máquina Virtual**: Escolha um nome para sua VM.
   - **Região**: Selecione a região geográfica onde deseja criar a VM.
   - **Imagem**: Escolha o sistema operacional para sua VM (por exemplo, Windows Server, Ubuntu).
   - **Tamanho**: Selecione o tamanho da VM com base na quantidade de CPU, memória, etc.

3. **Configurações de Administração**:
   - **Nome do Usuário**: Escolha um nome de usuário para acessar a VM.
   - **Autenticação**: Selecione entre senha ou chave SSH para autenticação.

4. **Configurações de Rede**:
   - Configure a rede virtual, sub-rede e escolha se deseja um endereço IP público.
   - Decida se deseja habilitar as portas de entrada (como RDP para Windows ou SSH para Linux).

### Passo 3: Revisar e Criar
1. **Revisar**: Revise todas suas configurações na guia "Revisar + Criar".
2. **Criar**: Clique em "Criar" para iniciar o provisionamento da máquina virtual.

### Passo 4: Acesso à Máquina Virtual
1. **Conectar**: Após o provisionamento, use as credenciais e o método de autenticação escolhido para acessar sua VM via endereço IP público ou através de ferramentas de gerenciamento de acesso remoto.

Este passo a passo ajuda a criar uma instância básica de máquina virtual na Azure. Certifique-se de configurar as opções avançadas conforme necessário para requisitos específicos de segurança e desempenho.
