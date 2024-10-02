# Dimensionamentos-em-M-quinas-Virtuais-na-Azure

Primeiro vamos Criar um VM: Clique em “Criar um recurso” e selecione “Máquina Virtual” ou pesquise na barra de pesquisa na área central superior.
. Configurações Básicas:
Assinatura: Selecione sua assinatura do Azure.
Grupo de Recursos: Escolha um grupo de recursos existente ou crie um novo.
Nome da Máquina Virtual: Dê um nome à sua VM.
Região: Escolha a região onde a VM será hospedada.
Imagem: Selecione o sistema operacional desejado (Windows ou Linux).
Tamanho: Escolha o tamanho da VM com base nas suas necessidades de CPU e memória.
vms
vamos Configurar Recursos
 Discos:
Disco do Sistema Operacional: Escolha o tipo de disco (SSD ou HDD).
Discos de Dados: Adicione discos adicionais conforme necessário.
 Rede:
Rede Virtual: Selecione uma rede virtual existente ou crie uma nova.
Sub-rede: Escolha uma sub-rede.
Endereço IP Público: Configure um endereço IP público se necessário.
Grupo de Segurança de Rede: Configure regras de firewall para controlar o tráfego de entrada e saída.
Passo 3: Dimensionamento
1. Dimensionamento Vertical:
Aumentar/Reduzir Tamanho: Você pode redimensionar a VM para um tamanho maior ou menor conforme necessário. Isso pode ser feito na seção “Tamanho” da VM no portal do Azure.
2. Dimensionamento Horizontal:
Conjuntos de Dimensionamento de Máquinas Virtuais: Use conjuntos de dimensionamento para criar e gerenciar um grupo de VMs idênticas. Isso permite que você escale automaticamente o número de VMs com base na demanda.
vamos Revisar e Criar
Revisar: Verifique todas as configurações.
Criar: Clique em “Criar” para provisionar a VM.
