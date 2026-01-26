# Resumo do Lab: Computação em Nuvem no Azure

Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO.

## ☁️ Conceitos de Nuvem Aprendidos

### 1. Modelos de Serviço (A Pirâmide da Nuvem)

* **IaaS (Infraestrutura como Serviço):** É como alugar um carro. O provedor cuida do hardware (motor, pneus), mas eu sou responsável por dirigir, colocar gasolina e fazer a manutenção do sistema operacional.
    * *Exemplo no Lab:* Criação da Máquina Virtual (VM) com Windows Server. Tivemos que configurar rede, tamanho da CPU e liberar portas.
* **PaaS (Plataforma como Serviço):** É como pedir um Táxi. O carro e o motorista já vêm prontos. Eu só digo o destino. A Microsoft cuida do Sistema Operacional e eu foco apenas no meu código ou dados.
    * *Exemplo no Lab:* Banco de Dados SQL do Azure. Não precisei instalar o SQL Server, apenas criei o banco e comecei a usar.
* **SaaS (Software como Serviço):** É como andar de Ônibus. A rota é fixa, tudo é gerenciado pela empresa. Eu apenas entro e uso o serviço.
    * *Exemplo:* O próprio portal do Azure, Microsoft 365, Gmail.

### 2. Modelo de Responsabilidade Compartilhada

A segurança na nuvem é uma parceria. Dependendo do modelo, a responsabilidade muda:

* **On-Premises (Local):** Sou responsável por TUDO (do ar-condicionado aos dados).
* **IaaS:** A Microsoft garante que o Datacenter não pegue fogo. Eu garanto que meu Windows não pegue vírus.
* **PaaS:** A Microsoft mantém o Windows atualizado. Eu protejo meus dados e aplicativos.
* **SaaS:** A Microsoft cuida de quase tudo. Minha responsabilidade principal é **proteger minha senha e meus dados**.

### 3. Principais Desafios Encontrados

Durante a criação da infraestrutura, aprendi na prática sobre:
* **Políticas de Região:** Algumas regiões (como West US) podem estar bloqueadas para assinaturas de estudante. A solução foi migrar para **East US**.
* **Gerenciamento de Custos:** A importância de excluir os Recursos e Grupos de Recursos ao finalizar o lab para não consumir os créditos.

  
<img width="352" height="527" alt="Captura de tela 2026-01-26 205015" src="https://github.com/user-attachments/assets/0f70cc07-0f6b-4e9d-9865-228eed9553fb" />
<img width="653" height="467" alt="Captura de tela 2026-01-26 205003" src="https://github.com/user-attachments/assets/f41c7b6b-a89f-408c-bee2-511173e1d727" />
<img width="595" height="418" alt="Captura de tela 2026-01-26 205010" src="https://github.com/user-attachments/assets/89869251-7b54-49f7-8201-c94d7d9e1607" />
