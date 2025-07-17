MAPA – Paradigma Lógico de Programação: Modularizando com Sub-Rotinas

Michael Ewerton Oliveira Disciplina: Paradigma Lógico de Programação Instituição: UniCesumar

Descrição do Projeto

Esta atividade abordou a importância do uso de sub-rotinas (funções e procedimentos) como forma de reduzir complexidade, melhorar organização e promover reutilização de código. O desafio consistiu em analisar um programa escrito em linguagem C que calcula alimentos e bebidas para um churrasco, identificando oportunidades de refatoração por meio da fragmentação funcional.

Estratégia Utilizada

O código original estava inteiro no bloco principal (main), o que dificultava a leitura e manutenção. Para torná-lo mais modular, foram sugeridas as seguintes sub-rotinas:

Sub-Rotina	Tipo	Responsabilidade
saudacao()	Procedimento	Exibir a mensagem inicial de boas-vindas ao usuário.
lerQuantidadePessoas()	Função	Retornar o número de participantes do churrasco.
calcularCarne()	Função	Retornar a quantidade de carne em kg com base na quantidade de pessoas.
calcularRefrigerante()	Função	Retornar a quantidade de refrigerantes em latas.
lerQuantidadeCervejeiros()	Função	Retornar o número de adultos que consomem cerveja.
calcularCerveja()	Função	Retornar a quantidade de cerveja em garrafas.
exibirResultados()	Procedimento	Mostrar os dados finais calculados na tela.
Justificativas das Escolhas

Funções foram utilizadas para todos os cálculos e entradas que geram valores — seguindo o princípio de que funções devem retornar dados úteis.

Procedimentos ficaram responsáveis pela apresentação visual e mensagens ao usuário — pois sua função é executar ação, sem retorno direto.

Resultado da Avaliação

Nota máxima (5,00/5,00) com destaque para:

Clareza na identificação das sub-rotinas

Justificação adequada de cada fragmentação

Correta diferenciação entre função e procedimento
