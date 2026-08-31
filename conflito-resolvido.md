# Conflito de merge controlado

## Oque ocorreu:
- Foi realizada na branch main uma alteração na linha 24 do README:
    - Conteúdo anterior: "Quanto aos demais pontos do projeto, a navegação não possui ordem definida.";
    - Conteúdo alterado: "Quanto aos demais pontos do projeto, a navegação é livre podendo passar por qualquer seção sem perda de entendimento.";
- Simultaneamente, foi realizada um alteração dessa mesma linha na branch feature/readme:
    - Conteúdo anterior: "Quanto aos demais pontos do projeto, a navegação não possui ordem definida.";
    - Conteúdo alterado: "Quanto aos demais pontos do projeto, é permitido navegar livremente sem qualquer prejuízo de compreensão.";

## Decisão:
- Após o conflito foi decidido que a alteração feita na branch feature/readme seria a escolhida para ser integrada no projeto;
- A decisão foi feita baseando em simplicitade e busca de evitar redundancias, sendo assim, foi escolhida a alteração feita na branch

## Resultado final:
- Após ser decidido que seria mantida a alteração feita na branch feature/readme, o código foi commitado e integrado ao repositório online, e a linha apresentou:
    - "Quanto aos demais pontos do projeto, é permitido navegar livremente sem qualquer prejuízo de compreensão."