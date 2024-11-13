Proxboard 
Um aplicativo para fazer o gerenciamento de máquinas virtuais (VMs) e virtualizadores.

Arquitetura do aplicativo:

- Página inicial com logo da empresa
    - Logo Branca centralizada 
    - Fundo preto
- Página de Login
    - Email e Senha
- Página Inicial com lista de VMs
- Menu Lateral
    - Lista de VMs (Home)
        - Header
            - Logo a esquerda
            - Botão para criar
            - Botão para modificar ou deletar
        - Corpo
            - Tabela com o hostname das VMs na primeira coluna e o ID na segunda
    - Lista de Virtualizadores
        - Header
            - Logo a esquerda
            - Botão para criar
            - Botão para modificar ou deletar
    - Resumo Geral
        - Total de VMs
        - Total de VMs ligadas/desligadas
        - Total de memória Ram VM
        - Total de vCPU VM
        - Total Disco VM
        - Total de virtualizadores
        - Total de memória Ram Virtualizador
        - Total de vCPU Virtualizador
        - Total Disco Virtualizador

Caracteristicas
- VMs
    - Hostname
    - ID
    - Memóriam Ram
    - vCPUs
    - Disco utilizado
    - Virtualizador utilizado
- Virtualizadores
    - Hostname
    - ID
    - Memóriam Ram
    - vCPUs
