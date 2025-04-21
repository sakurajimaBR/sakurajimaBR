# Desafio: Criação de Máquina Virtual na Azure

Este repositório faz parte da minha jornada de aprendizado com a plataforma Microsoft Azure. Neste desafio, realizei a criação e configuração de uma máquina virtual (VM) como parte prática dos módulos do curso.

## Objetivo

Aplicar na prática os conhecimentos adquiridos sobre a Azure, documentando os passos e reunindo anotações e dicas que possam servir como material de apoio para revisões futuras e novos projetos.

## O que você vai encontrar aqui

- Resumo dos principais conceitos aprendidos
- Etapas realizadas para criar e configurar a VM
- Dicas úteis para quem está começando na Azure
- Anotações pessoais que me ajudaram no processo

## O que aprendi até agora

- Criar e gerenciar uma conta no portal da Azure
- Navegar pela interface e entender os serviços principais
- Criar uma máquina virtual: escolha do SO, tamanho, rede e credenciais
- Importância da documentação técnica clara e organizada
- Uso do GitHub para versionamento e compartilhamento de conteúdo

## Anotações e Dicas sobre o uso da Azure

### Conceitos Básicos

- **Azure Resource Group**: É como uma pasta onde você organiza seus recursos. Sempre que for criar uma VM, pense no grupo como a base que mantém tudo junto.
- **Região (Region)**: Escolha uma região próxima de você ou dos usuários do serviço para melhorar a performance.
- **Tipos de VMs**: A Azure oferece vários tamanhos de máquina (ex: B1s, D2s, F2s), com preços e capacidades diferentes. Para testes, use as mais leves e gratuitas, se possível.
- **Imagens de SO**: Você pode escolher entre Windows, Ubuntu, Debian, entre outros. Eu usei o Ubuntu Server 20.04 LTS para essa prática.

### Dicas Práticas

- **Tags**: Use tags para organizar os recursos (ex: ambiente=teste, projeto=curso).
- **Conexão SSH (para Linux)**: Após criar a VM, você pode conectar por terminal usando o comando:
  ```bash
  ssh nome-de-usuário@ip-da-vm
