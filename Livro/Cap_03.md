# Capítulo 03 - Requisitos

> The hardest single part of building a software system is deciding precisely what to build. – Frederick Brooks

Os **requisitos** são importantíssimos para um projeto, já que são eles que vão guiar a forma como um projeto é feito. Eles servem para informar o que um sistema deve fazer (**requisitos funcionais**) e sob quais restrições devem ser feitos (**requisitos não-funcionais**). Caso um requisito não tenha sido levantado corretamente, ele pode acarretar em um grande problema no produto final, pois pode não ser útil para o usuário.

Requisitos funcionais normalmente são escritos em linguagem natural e os não-funionais são descritos de forma quantitativa, isso serve para que não ocorrar específicações genéricas, com "o sistema deve ser rápido".

### Engenharia de Requisitos

Funciona como uma forma de trazer para os desenvolvedores exatamente o que o cliente deseja, tanto recebendo o que ele fala quanto tratando e especificando em uma linguagem mais técnica. Após serem levantados, devem ser documentados(1), validados e documentados(2) e priorizados(3). No caso do ágil, a documentação é feita em histórias de usuários (_user stories_).

#### <u>Requisitos devem ser:</u>

`corretos` - caso um requisito não seja descrito da formar correta pode gerar em perdas para o cliente, ex.: fórmulas matemáticas, datas, capacidade, etc.  
`precisos ` - um requisito não pode ser ambíguo, isso acontece bastante com os requisitos funcionais pois eles são escritos em linguagem natural.  
`completos` - não pode ser deixado de especificar um requisito, principalmente se ele for importante.  
`consistentes` - não deve ocorrer inconsistências entre diferentes partes do projeto, ex.: um stakeholder afirma que a disponibilidade do sistema deve ser 99,9% e outro considera que 90% já é suficiente.  
`verificáveis` - deve ser possível testar se um requisito está sendo atendido.
