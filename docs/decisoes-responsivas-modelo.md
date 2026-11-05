# Plano responsivo do meu projeto

Projeto: Estodolist - Gustavo S

## Celular (360 px)

- O que fica empilhado e em que ordem os blocos aparecem?
- O que pode ficar escondido?

Minha resposta: 
- Empilha nome da atividade, descrição, categoria, data, prioridade e após isso, mostra todas as tarefas listadas.
- Fica escondido o texto "Organize seus estudos".

## Tablet (768 px)

- O que ganha espaço e pode ficar lado a lado?
- O que passa a mostrar mais informação?

Minha resposta:
- Fica o inserir tarefa na esquerda e as tarefas listadas na direita.
- Mostra mais informações das atividades e deixa tudo mais visível e bonito.

## Notebook (1280 px)

- Quais blocos viram colunas?
- O que fica fixo, aparece ou some?

Minha resposta:
- Os blocos que viram colunas são os da esquerda, de inserir tarefa e as tarefas, ficam na horizontal.
- Aparece tudo que está na tela inicial.

## Padrões que vou usar

Marque o que combina com o seu plano (consulte o slide "Cardápio de padrões" e a documentação do Tailwind):

- [x] Colunas com grid (`grid`, `grid-cols-N`, `col-span-N`)
- [x] Itens em linha com flex (`flex`, `flex-col`, `md:flex-row`)
- [x] Algo escondido em telas pequenas (`hidden` + `md:block`)
- [x] Algo fixo ao rolar (`lg:sticky`)
- [x] Outro:

## Depois de construir (preencha ao final)

Uma decisão do plano mudou durante a construção? Qual e por quê?

Resposta: Sim. Durante a construção, ajustei a organização dos elementos para melhorar a responsividade. Utilizei md:grid-cols-2 e lg:grid-cols-4 para adaptar o layout a diferentes tamanhos de tela, além de lg:sticky para manter o formulário visível durante a rolagem, facilitando o uso da página.
