## Análise de Conteúdo com Discurso do Sujeito Coletivo (DSC) usando Python

Este Notebook visa facilitar a compreensão da análise do *Discurso do Sujeito Coletivo* por meio de métodos computacionais, oferecendo uma abordagem prática e automatizada para a interpretação de dados qualitativos.

Este projeto **ainda em desenvolvimento**, tem como objetivo realizar uma análise de conteúdo utilizando o método "Discurso do Sujeito Coletivo" (DSC), proposto por Fernando Lefèvre e Ana Maria Cavalcanti Lefèvre, professores da Faculdade de Saúde Pública da USP. O DSC é uma abordagem na pesquisa qualitativa que busca identificar ideias centrais e representações coletivas a partir das respostas de entrevistados.

#### Setup de Módulos
Antes de iniciar, é preciso instalar as bibliotecas necessárias. Utilizando os comandos !pip install para instalar os módulos necessários.

#### Obtendo respostas das entrevistas
O código lê as respostas coletadas por meio de formulários eletrônicos ou das transcrições de entrevistas estruturadas por meio de audio ou vídeo, que são convertidas em um arquivo CSV para facilitar a manipulação. Esse passo é essencial para preparar os dados da análise subsequente.

#### Definindo Expressões Chave e categorizando as Ideias Centrais
Nesta etapa, são utilizados modelos linguísticos para extrair entidades nomeadas e palavras-chave relevantes das respostas. A ideia central do Discurso do Sujeito Coletivo é formada pela combinação desses elementos.

#### Gráfico de distribuição dos dados categóricos
Um gráfico de barras é gerado para visualizar as palavras mais frequentes nas respostas, proporcionando insights sobre os temas mais recorrentes.

#### Obtendo modelos treinados
Para gerar a chave API na conta OpenAI:
1. Criar uma conta no site: https://platform.openai.com/signup
2. Posicionar o cursor do mouse sobre o ícone do OpenAI que fica no canto superior direito da tela, e depois clique na opção "API keys".
3. Clicar em "Create new secret key", depois copiar a chave gerada.

O resultado final do valor deve ser algo parecido com: `sk-js4rL9e3OBr6B67mx2YwT5BlbkFJ4otgcWD08MX0VLkRG9In`

#### Realizando Análise do Discurso do Sujeito Coletivo
O código utiliza o modelo ChatGPT da OpenAI para gerar um parágrafo formal a partir das ideias centrais identificadas. O resultado é apresentado com formatação, proporcionando uma visualização mais amigável.

> Esta abordagem não visa substituir os métodos empíricos e softwares existentes na aplicação do DSC, mas proporcionar ao pesquisador outras estratégias para facilitar a precisão do processo, visando complementar e oferecer opções adicionais, possibilitando escolher entre diferentes estratégias para melhorar na acurácia dos resultados obtidos ao utilizar métodologia do *Discurso do Sujeito Coletivo*.

#### Uso
As reproduções, melhorias e adaptações deste trabalho ficam condicionados a citar o autor [RAMOS, E. S.](http://lattes.cnpq.br/3207935358521360)

#### Referências
> LEFEVRE F; LEFEVRE A.M.C. [**O discurso do sujeito coletivo: um novo enfoque em pesquisaqualitativa (desdobramentos)**](https://repositorio.usp.br/item/001347796). Caxias do Sul: EDUCS, p. 256. 2003.