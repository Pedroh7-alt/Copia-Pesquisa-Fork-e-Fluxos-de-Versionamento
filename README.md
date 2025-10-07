
   //Em suas palavras, o que é **fork** e quando usar? Dê 1 exemplo simples: 

   Um fork é uma cópia de um repositório existente que é criada em sua conta no GitHub. Ele permite que você faça alterações no código sem afetar o repositório original, conhecido como "upstream". Forks são amplamente utilizados para colaborar em projetos de código aberto ou para trabalhar em ideias sem permissão de gravação no repositório original.
   


   - Qual a diferença entre **fork**, **clone** e **branch**? Explique cada um em **uma frase**.  

    Fork: Criação de uma cópia independente de um repositório, geralmente usado para contribuir com projetos de código aberto.

    Clone: Cópia local de um repositório remoto, usada para desenvolver ou explorar o código em sua máquina.

    Branch: Uma linha paralela de desenvolvimento dentro do mesmo repositório, usada para trabalhar em novos recursos ou correções sem afetar o código principal.



   - Compare **GitHub Flow**, **Git Flow** e **Trunk-Based Development**: como funcionam e quando fazem mais sentido (ex.: deploy frequente, projetos com “releases” formais, turmas pequenas etc.).  

   GitHub Flow:  O desenvolvedor cria uma branch a partir da main, faz alterações e submete um pull request para revisão.
    Quando usar: Ideal para projetos com deploy frequente e equipes pequenas ou com desenvolvimento contínuo.

   Git Flow:
    Utiliza branches como master, develop, feature, release e hotfix, com ciclos mais estruturados de integração e lançamento.
       Quando usar: Projetos com lançamentos formais e ciclos de desenvolvimento mais complexos, como aplicativos empresariais.

Trunk-Based Development:
    Todos os desenvolvedores fazem mudanças diretamente na main ou trunk, com pequenas e rápidas atualizações diárias.
        Quando usar: Ideal para equipes que precisam de deploy contínuo e rápidos feedbacks, como startups ou equipes ágeis.


   - O que é um **Pull Request** e por que ele é importante na colaboração? 

Um Pull Request (PR) é uma solicitação para que as mudanças feitas em uma branch sejam revisadas e integradas ao repositório principal. Ele é importante porque permite que outros desenvolvedores revisem o código, discutam possíveis melhorias, identifiquem erros e garantam que as mudanças não afetem negativamente o projeto principal. Além disso, ele facilita a comunicação dentro da equipe e melhora a qualidade do código. 