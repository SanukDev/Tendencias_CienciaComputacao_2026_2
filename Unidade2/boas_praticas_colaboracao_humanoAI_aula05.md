### Boas Práticas para Colaboração Humano-IA

1. Avaliação Crítica e Inspeção Rápida: Em vez de aceitar o código cegamente, o programador deve realizar uma avaliação "impressionista" e rápida, focando em *diffs* (diferenças de código), palavras-chave e estruturas para verificar se a saída atende aos requisitos.
2. Gerenciamento Estratégico de Contexto: É essencial fornecer à IA recursos como documentação técnica externa e instruções de sistema personalizadas (ex: arquivos `.cursorrules`), além de "limpar" o contexto entre diferentes fases para reduzir alucinações.
3. Intervenção Manual Seletiva: O desenvolvedor deve saber identificar quando a edição direta do código é mais eficiente do que continuar refinando *prompts*, especialmente em correções simples ou na resolução de bugs complexos que a IA não consegue diagnosticar sozinha.

### Síntese da Colaboração Responsável

Programar com IA de maneira responsável não significa apenas saber pedir código; 
significa também manter uma supervisão estratégica e seletiva sobre a produção mediada pela tecnologia.
A prática exige que a confiança seja construída através da **verificação iterativa** em vez de uma aceitação cega, redirecionando a expertise humana para a avaliação rápida de código e o gerenciamento de contexto. 
Além disso, o desenvolvedor deve assumir o papel de orquestrador, decidindo conscientemente quando transitar do auxílio da IA para a **intervenção manual direta** para garantir a integridade e a funcionalidade do sistema. 
O desenvolvedor deve estar ciente também de que qualquer decisão tomada é de responsabilidade do usuário e não da ferramenta, e que quaisquer consequências devem ser direcionadas ao desenvolvedor, pois foram tomadas decisões conscientes por meio de pedidos elaborados, mas que sozinhos, sem a interação humana, não poderiam ser levados adiante.
