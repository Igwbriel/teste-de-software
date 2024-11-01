## Tema do artigo:
Comparando a efetividade de testes de software: Desenvolvedores vs chatGPT na geração de casos de teste 

## resumos dos artigos lidos: 

##### CHATGPT: UMA ANÁLISE DA FERRAMENTA APLICADA NO PROCESSO DE DESENVOLVIMENTO DE SOFTWARE

Este trabalho examina o uso do ChatGPT como uma ferramenta auxiliar no desenvolvimento de software, aplicando-o em uma aplicação de gestão para uma cafeteria. A pesquisa analisa como o ChatGPT pode ser usado na modelagem de requisitos, na geração de código e na criação de testes automatizados. Para isso, a aplicação foi estruturada na arquitetura hexagonal, que facilita a modularidade e os testes, permitindo observar com clareza os benefícios e as limitações da IA em um ambiente de desenvolvimento prático. O ChatGPT foi utilizado para auxiliar na criação de histórias de usuário, no desenvolvimento de classes e métodos, e na execução de testes unitários, mostrando-se útil para aumentar a produtividade e simplificar tarefas repetitivas.

Os resultados indicam que o ChatGPT pode acelerar o desenvolvimento e otimizar processos específicos, mas também destacam a importância da supervisão humana. Embora a IA forneça sugestões relevantes, o conhecimento técnico do desenvolvedor é indispensável para adaptar essas respostas, garantindo que estejam alinhadas às melhores práticas e ao contexto específico do projeto. O estudo conclui que, enquanto o ChatGPT traz ganhos de eficiência, a intervenção humana é fundamental para validar e ajustar o código, fazendo da IA uma ferramenta complementar, mas não substitutiva, no processo de desenvolvimento de software.

[Link para o artigo](https://repositorio.pucgoias.edu.br/jspui/handle/123456789/7929)

##### UTILIZAÇÃO DE CHAT BOTS BASEADOS EM LLMS PARA AUTOMAÇÃO DE TESTES DE SOFTWARE

O trabalho investiga o uso de chatbots baseados em Grandes Modelos de Linguagem (LLMs) como suporte para a automação de testes de software, focando na ferramenta Cypress para testes de interface de login. São testados cinco LLMs – ChatGPT, Google Bard, Aria Opera, Microsoft Bing e Perplexity AI – em três modelos de prompts (Explícito Básico, Explícito Detalhado e BDD/Gherkin). Os testes abrangem dez cenários de login, totalizando 150 testes, com o objetivo de avaliar a precisão e confiabilidade de cada modelo em gerar código de teste.

Os resultados indicam alta eficácia na maioria dos LLMs, com destaque para Google Bard (93% de precisão) e Aria Opera (90%), enquanto Perplexity AI apresentou uma taxa de acerto de 73%. A pesquisa conclui que esses modelos podem ser úteis na automação de testes, mas reforça a necessidade de supervisão humana para assegurar a adequação e eficácia das respostas. A análise também discute limitações e sugere aprimoramentos para a aplicação dos LLMs, apontando seu potencial como ferramentas complementares no processo de desenvolvimento e testes de software.

[Link para o artigo](https://monografias.ufop.br/handle/35400000/6440)

##### Evaluating and Improving ChatGPT for Unit Test Generation

Este artigo avalia a eficácia do ChatGPT na geração de testes unitários e propõe melhorias para aprimorar a precisão dos testes gerados. A pesquisa revela que, embora o ChatGPT consiga produzir testes com qualidade comparável aos escritos manualmente em termos de cobertura e legibilidade, muitos dos testes ainda apresentam problemas de compilação e execução, principalmente devido a erros nas asserções. Para enfrentar essas limitações, os autores desenvolveram o **ChatTester**, uma abordagem iterativa que usa o próprio ChatGPT para refinar e corrigir os testes gerados. O ChatTester integra duas etapas principais: um gerador inicial de testes e um refinador iterativo, permitindo uma melhoria substancial na taxa de sucesso dos testes.

O estudo foi baseado em um benchmark com 1.000 métodos Java, onde os testes gerados pelo ChatGPT foram avaliados em critérios como correção, suficiência, legibilidade e usabilidade. Além disso, o ChatTester foi aplicado a outros modelos de linguagem, como CodeLlama-Instruct e CodeFuse, mostrando sua capacidade de generalização. Nos testes, o ChatTester aumentou em 34,3% a taxa de testes compiláveis e em 18,7% a taxa de testes executados corretamente em comparação ao ChatGPT padrão. Esses avanços reforçam o potencial dos LLMs na geração de testes de software de alta qualidade, embora ainda haja a necessidade de intervenção humana para garantir precisão total.

[Link para o artigo](https://dl.acm.org/doi/abs/10.1145/3660783)
