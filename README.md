Esse é um projeto que eu criei como exercício de aprendizado. A ideia foi montar um formulário completo de matrícula para uma escola infantil fictícia chamada **Estrelas do Amanhã**. 

Tudo foi feito com HTML e CSS, tentei aplicar várias boas práticas que venho estudando, como organização de arquivos, uso de variáveis CSS, layout com grid e componentes reutilizáveis.

## Objetivo

Permitir que os responsáveis preencham os dados da criança e finalizem a matrícula de forma clara e organizada, com uma interface amigável.

## Tecnologias usadas

- HTML semântico;
- CSS moderno (com variáveis, grid e flexbox);
- CSS modularizado (cada parte do layout ou componente em um arquivo separado);
- Ícones em SVG para personalização dos campos (checkbox, radio, etc....);
- Responsividade mobile-first com ajustes para desktop.

## O que o formulário temww

- Dados da criança: nome, nascimento, sexo e observações médicas;
- Upload de certidão de nascimento;
- Endereço com preenchimento automático de cidade e estado (simulado);
- Dados do responsável legal;
- Escolha de turno e atividade esportiva;
- Confirmação de leitura dos termos;
- Botões de ação: salvar e enviar matrícula.

## Responsividade

A interface foi construída com abordagem **mobile-first**, utilizando `flex-direction: column-reverse` para exibir o conteúdo institucional acima do formulário em telas pequenas. Para telas maiores (acima de 1024px):

- O layout muda para **CSS Grid**, dividindo a tela em duas colunas (formulário e lateral);
- Utiliza-se **padding fixo de 25px** em `main` e `aside` para garantir respiro visual mesmo com zoom ativado;
- Foi evitado o uso de `height: 100vh` em `main` para prevenir cortes visuais, especialmente em notebooks e resoluções menores.

Se você tiver qualquer sugestão ou dica, vou ficar muito feliz em aprender mais!
