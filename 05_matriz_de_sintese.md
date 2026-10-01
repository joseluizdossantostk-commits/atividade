# Etapa 5 Matriz de síntese e organização da revisão

## Solicitação

Compare os artigos e organize a revisão por temas ou eixos. Não produza apenas uma sequência de resumos.

## Eixos da revisão

1. Padrões de Programação e Semântica do Código HTML/Mobile (Focado nas falhas de estrutura técnica).
2. Experiência de Uso dos Sistemas Assistivos e Conflitos de Áudio (Focado no impacto prático sobre o usuário).
3. `[Eixo ou subtema 3, se necessário]`

## Matriz de síntese

|Eixo|Artigos relacionados|Convergências|Divergências|Limitações|Lacunas|
1. |Eixo|Programação e Semântica de Código|Experiência de Uso e Conflitos de Áudio|
2. |Artigos relacionados|Reis & Silva (2022); Mendes & Almeida (2024)|Reis & Silva (2022); Souza & Oliveira (2025)|
3. |Convergências|Ambos apontam que a principal barreira técnica é a falta de tags (alt, aria-label) e de foco programático em elementos dinâmicos durante o desenvolvimento.|Ambos concordam que a aprovação mecânica em validadores automáticos não garante que o áudio final gerado fará sentido e será confortável para o deficiente visual.
4. |Divergências|Reis & Silva focam no ambiente Web público e de páginas estáticas, enquanto Mendes & Almeida detalham a complexidade dos Apps Mobile e suas atualizações em tempo real.|Reis & Silva abordam a fadiga provocada pela leitura exaustiva de menus, enquanto Souza & Oliveira focam no conflito físico de volume e sobreposição sonora de áudios concorrentes.
5. |Limitações|Os estudos focaram em grandes portais ou empresas, deixando de fora pequenos sites locais ou startups|Foco teórico em diretrizes internacionais (WCAG), sem explorar variações causadas por softwares leitores gratuitos regionais ou de código aberto.
6. |Lacunas|Falta analisar como ferramentas modernas de IA generativa de código podem auxiliar desenvolvedores a preencher essas tags automaticamente.|Pouca discussão sobre a inclusão de feedbacks por comandos de voz bidirecionais (onde o usuário também dita ações em vez de apenas ouvir).

## Roteiro da revisão da literatura

### Eixo 1 | Padrões de Programação e Semântica do Código HTML/Mobile

* Ideia principal: As barreiras de acessibilidade digital para deficientes visuais não são falhas das tecnologias assistivas, mas sim consequências diretas da ausência de semântica correta durante a codificação das interfaces.
* Evidências que serão usadas: A estatística de que menos de 1% das imagens em portais analisados possuem textos alternativos funcionais (Reis & Silva, 2022) e o dado de que 70% dos desenvolvedores mobile não possuem treinamento formal em acessibilidade para gerenciar árvores de elementos dinâmicos (Mendes & Almeida, 2024).
* Comparação entre estudos: Enquanto Reis & Silva (2022) destacam o impacto dessa omissão de código na navegação linear de sites públicos, Mendes & Almeida (2024) elevam essa discussão ao ambiente móvel, onde pop-ups e elementos assíncronos quebram o foco do leitor de tela por completo.
* Ligação com o problema: Responde à pergunta de pesquisa ao identificar que a ausência de parametrização básica de engenharia de software é um dos principais desafios técnicos que inviabilizam o uso de recursos de áudio.

### Eixo 2 | Experiência de Uso dos Sistemas Assistivos e Conflitos de Áudio

* Ideia principal: A validação automatizada de acessibilidade é insuficiente se não considerar fatores de usabilidade humana, como a fadiga cognitiva provocada pela poluição sonora e pela sobreposição de faixas de áudio.
* Evidências que serão usadas: Os testes de usabilidade com usuários cegos evidenciando cansaço mental extremo devido à falta de atalhos ("ir para o conteúdo") (Reis & Silva, 2022) e os conflitos técnicos de áudio concorrente (reprodutor de audiodescrição vs. sintetizador de voz do sistema operacional) (Souza & Oliveira, 2025).
* Comparação entre estudos: Reis & Silva (2022) tratam a experiência do usuário sob a ótica da navegação estrutural cansativa, ao passo que Souza & Oliveira (2025) aprofundam-se nas deficiências das diretrizes normativas da WCAG ao lidarem com o controle de volume concorrente na reprodução multimídia.
* Ligação com o problema: Esclarece os desafios operacionais do nosso problema de pesquisa, demonstrando que mesmo quando um recurso de áudio é inserido, sua falta de sincronia sonora impede a autonomia real do usuário.

## Síntese crítica provisória

A literatura científica recente demonstra de maneira inequívoca uma tendência de convergência: o grande gargalo da inclusão digital não reside no software assistivo utilizado pelo deficiente visual, mas sim no desconhecimento técnico das equipes de desenvolvimento sobre arquitetura de informação acessível. No entanto, persistem divergências operacionais sobre como aplicar as regras da WCAG em ambientes dinâmicos e mobile sem gerar sobreposição de áudio ou poluição sonora. A principal lacuna identificada nos estudos atuais reside na falta de pesquisas práticas voltadas para a automação desse processo de acessibilidade em equipes que utilizam metodologias ágeis, bem como na baixa representatividade de testes envolvendo leitores de tela gratuitos e regionais.

## Checklist

* [X] Os artigos foram agrupados por ideias.
* [X] Há comparações entre estudos.
* [X] As divergências foram registradas.
* [X] As lacunas são específicas e sustentadas pelas leituras.

