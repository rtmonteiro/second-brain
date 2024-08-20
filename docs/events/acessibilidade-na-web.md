# Web Inclusiva: Tornando a Internet Acessível para todos

## Descrição

Você já sentiu que um espaço não foi pensado para você? Talvez um ambiente com um idioma desconhecido, algum local apertado ou muito alto, ou seja, algum lugar que você não consiga acessar. Na Web não é diferente, por isso vamos aprender algumas ferramentas e diretrizes que auxiliam o conteúdo a ser transmitido para todos de forma acessível, independente da interface que esteja utilizando, seja navegando através do toque na tela, pelo mouse, somente com um teclado ou até por voz. Ao entendermos a importância de desenvolver essa multiexperiência, temos como resultado uma aplicação com qualidade de código, acessível e leve.

## Objetivos

1. Desmitificar para que e para quem serve a Acessibilidade
1. Intensificar a importância da Web Semântica
1. Apresentar os principais atributos HTML sobre acessibilidade
1. Demonstrar como funcionam as ferramentas de verificação de acessibilidade na web
1. Finalizar com boas referências para continuarem pesquisando

## Roteiro

Começar comunicando "Bom dia à todos, o tema dessa palestra é acessibilidade na Web" em libras e logo depois perguntando como alguém que não fala Libras se sentiu, e explicando como algumas pessoas se sentem durante o dia a dia

Exemplos de espaços não acessíveis:

- Ao se acidentar e precisarmos usar uma muleta ou cadeira de rodas e descobrimos que muitos espaços não foram pensados para todos;
- Viajar para outro país e não saber a língua nativa;
- Ir ao oftalmologista e fazer o procedimento de fundo de olho para dilatar a pupila, e ao voltarmos pra casa não conseguir pedir um uber.

As interfaces podem ser inacessíveis de uma hora para outra, basta surgir uma barreira de comunicação para sentirmos a necessidade de ferramentas que nos ajude a derrubar essa limitação.

Na web não é diferente, diversos Portais, Sites ou Aplicativos não são pensados para usos intuitivos além da tela. Imagine que no momento de pedir um uber você pudesse falar com seu celular "favor pedir um Uber para casa" e o dispositivo prontamente chamasse um carro para você.

Imagine que você está a caminho de casa, e lembra que precisa ler um artigo sobre as notícias do último semestre de investimentos no mercado financeiro. O seu navegador possui uma funcionalidade que lê somente a parte do conteúdo do artigo e você consegue escutar as palavras da matéria ignorando todo resto da estrutura do site.

Porém isso só é possível se o desenvolvedor fez o site com o conhecimento de web semânctico, que não é algo complicado, é somente a forma de dizer para o navegador o que é aquele elemento.

Pois da mesma forma que a web permite o dev construir um site utilizando somente `div` e `span`, a consequência é que o navegador não vai entender qual o comportamento esperado do seu elemento, e você perde uma grande ajuda em apresentar as informações para um público maior do que somente a tela alcança.

Outro importante grupo de atributos da web para a acessibilidade são os atributos ARIA, que aumentam a descrição daquele elemento, e empoderam o navegador e outras ferramentas de acessibilidade a passar para o usuário final uma visão mais completa do que esperar dele.

O atributo `role` permite indicar o comportamento que um elemento div deve se comportar igual um modal. O atributo `tabindex` descreve a sequência de aninhamento que os elementos devem seguir, se uma lista está dentro de um submenu que está dentro de outro submenu.

Só o `role` possui mais de 80 valores para aumentar a descrição daquele elemento, e isso tem impacto em como o foco do usuário deve ser.

Existem padrões a seguir definidos pela Web Content Accessibility Guidelines (WCAG), que descrevem uma base de critérios para alcançar um produto digital verdadeiramente inclusivos e acessíveis.

Alguns exemplos de ações que o guia descreve:

- **1.1.1 - Conteúdo não textual**: Qualquer conteúdo "não textual" e relevante para compreensão da informação, deve trazer uma descrição alternativa em texto (visível ou não) para identificar o conteúdo (inclusive captcha, por exemplo).

- **1.4.1 - Utilização de cores**: Cores não devem ser utilizadas como única maneira de transmitir conteúdo ou distinguir elementos visuais, para evitar que baixo constrante ou qualquer outro motivo de distinção visual cause erros no uso. Uma cenário é, uma mensagem de erro em um formulário deve trazer um ícone de alerta.

Apresentar algumas ferramentas de testes de Acessibilidade, como Leitores de Tela, Testadores de contraste, Validadores de acessibilidade.

Alguns retornos para sites que utilizam acessibilidade

- Mais fácil de desevolver e fazer manutenção
- Código mais leve
- Mais eficiente para o SEO

Concluir com a reflexão de que todos se beneficiam com espaços planejados e desenvolvidos para a inclusão da maior quantidade de pessoas.

## Links

- [Título e Descrição](https://medium.com/womakerscode/speaker-tips-criando-uma-proposta-de-palestra-461d1cf187f4)
- [Como organizar uma palestra](https://rockcontent.com/br/blog/como-organizar-uma-palestra/)

## Referências

- [Cartões de Acessibilidade](https://guia-wcag.com/)
- [O que é ARIA?](https://web.dev/articles/semantics-aria?hl=pt-br)
- [Era da Multiexperiência](https://edu.ieee.org/br-ufcgras/era-da-multiexperiencia-o-caminho-para-a-transformacao-digital/)
