# Navigation Compose - Checkpoint 1

## Descrição do Projeto
Este projeto continua a atividade anterior e aplica navegação entre telas com Jetpack Compose Navigation, incluindo passagem de parâmetros.

## Objetivo
Implementar as seguintes melhorias no projeto:

- Passagem de parâmetro obrigatório na tela de Perfil
- Passagem de parâmetro opcional na tela de Pedidos
- Envio de valor em parâmetro opcional
- Passagem de múltiplos parâmetros entre telas

## Histórico de Commits

### Primeiro Commit — Parâmetro obrigatório na tela de Perfil
A tela de perfil passou a receber o nome como parâmetro, deixando de ser fixa.  
A navegação do menu foi atualizada para enviar esse nome ao abrir a tela.  
A rota também foi configurada com valor padrão caso nenhum nome seja informado.

### Segundo Commit — Parâmetro opcional na tela de Pedidos
A tela de pedidos passou a receber o cliente como parâmetro e exibi-lo na tela.  
A rota foi configurada para aceitar esse valor como opcional, com valor padrão.  
Também foi adicionado o import necessário para trabalhar com argumentos na rota.

### Terceiro Commit — Envio de valor no parâmetro opcional
A navegação do menu foi alterada para abrir a tela de pedidos já enviando um cliente específico.

### Quarto Commit — Múltiplos parâmetros na tela de Perfil
A tela de perfil passou a receber também a idade como parâmetro.  
O texto foi atualizado para mostrar nome e idade.  
A navegação do menu foi ajustada para enviar os dois valores.  
A rota foi configurada para receber nome como texto e idade como número.