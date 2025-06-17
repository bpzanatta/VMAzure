VMAzure – Minha Jornada no Gerenciamento de Máquinas Virtuais no Azure

Durante este desafio da DIO, explorei na prática como criar, gerenciar e monitorar Máquinas Virtuais (VMs) no Microsoft Azure.
Decidi montar este repositório como um material de consulta pessoal, mas que também pode ajudar quem está começando a trabalhar com Azure.

📝 O que eu aprendi

Entendendo o conceito de VMs no Azure:
O que são, como funcionam, tipos de tamanhos (SKU) e como escolher a região certa para implantação.

Criando VMs de diferentes formas:
Testei a criação via Portal do Azure, Azure CLI e até com PowerShell.
Cada método tem suas vantagens dependendo do cenário.

Gerenciando as VMs:
Descobri como iniciar, parar, reiniciar e até como redimensionar uma VM quando precisei de mais performance.
Também mexi com discos adicionais (Data Disks) para testar armazenamento extra.

Configurando o acesso e conectividade:
Configurei NSGs (Network Security Groups), abri portas para RDP e SSH, e configurei IPs públicos e privados.

Automatizando o provisionamento:
Aprendi um pouco de Infraestrutura como Código criando VMs com scripts de CLI e entendi o básico de ARM Templates e Bicep.

Monitorando desempenho:
Ativei o Azure Monitor, coletei métricas como uso de CPU, disco e memória, e até criei um dashboard simples no portal.

Segurança:
Experimentei o Azure Bastion para acesso seguro às VMs sem IP público e entendi o papel da Managed Identity.

💡 Dicas que funcionaram bem pra mim

Sempre que possível, automatize a criação das VMs (evita erros e ganho de tempo).

Use tags nos recursos desde o início para facilitar a organização e o monitoramento de custos.

Habilite monitoramento e logs logo após criar a VM. Fica mais fácil diagnosticar problemas depois.

📚 Fontes que me ajudaram muito

Documentação oficial: Gerenciar VMs no Azure

Anotações feitas durante o curso na DIO
