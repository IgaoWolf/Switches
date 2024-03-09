# Switches
 Comandos Switches

Switch Huawei:

Entrar em modo de configuração:

system-view

Configurar interface GigabitEthernet 2/0/31:

interface GigabitEthernet 2/0/31

Remover VLANs da interface:

undo port hybrid tagged vlan 3
undo port hybrid tagged vlan 5

Exibir configuração da VLAN:

display vlan

Remover VLANs específicas (3, 5, 7, 10, 800):

undo vlan 3
undo vlan 5
undo vlan 7
undo vlan 10
undo vlan 800


Switch Dell:

Entrar em modo de configuração:

configure

Configurar interface VLAN 3 e desativá-la:

interface Vlan 3

Salvar configuração no switch Dell:

copy running-config startup-config

Observações:

Certifique-se de estar no modo privilegiado para executar comandos de configuração no switch Dell (usando enable).
Para alterar a descrição de uma porta, use o comando:

description "porta datacenter"
alterações desejadas.