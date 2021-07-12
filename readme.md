# Desafio Técnico

## Desafio proposto

Foi proposta um desafio técnico, em uma atividade da GI/Ford

O desafio foi baseado em implementar a criptografia. inicialmente foi previsto uma criptografia baseada na criptografia de Julio Cesar. A diferença seria que não seria somado um código aos caracteres e sim multiplicado. No entanto, durante o desenvolvimento percebi que essa solução não funcionaria corretamente. Com isso o desenvolvimento foi a própria criptografia de Cesar.


Ex.:
- O caracter "A" será trocado pelo caracter "E";
- o caracter "B" será trocado pelo caracter "F";
- o caracter "C" será trocado pelo caracter "G";
- e assim por diante.

## Decisões tomada pela equipe

1. Utilizar a tabela ascii para fazer a criptografia
2. Possibilitar a criptografia não só de letras, mas sim de qualquer caracter ascii, pois assim poderá ser encriptado números, pontuações, acentução gráfica, etc.

## O que faltou fazer

Pela curto tempo optei em não desenvolver testes de unidade. No entanto na chamada da função implementei um pseudo teste