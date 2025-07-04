# Introdução à Ciência dos Dados - 2025/1

Este repositório contém materiais e projetos desenvolvidos para 
a disciplina de Introdução à Ciência dos Dados do Bacharelado 
em Administração do IFMG - Campus Formiga, cursada no primeiro 
semestre de 2025.


## O que estou aprendendo nesta disciplina?

Nesta disciplina, estou aprendendo fundamentos de Ciência de Dados. 
Isso inclui:

- Como aplicar a metodologia CRISP-DM em projetos de análise de dados
- Como usar o IDE RStudio
- Como criar relatórios com o sistema Quarto
- Como organizar projetos de análise de dados
- Como trabalhar com o Git e GitHub
- Como usar a linguagem R para analisar dados


## Estrutura do projeto (Organização das Pastas)

- **dados/**
  - **brutos/**: Arquivos de dados originais
  - **limpos/**: Dados organizados após processamento
  
- **relatorios/**
  - **01_relatorio/**: relatório quarto no formato html
  - **02_relatorio/**: relatório quarto no formato pdf
  - **03_relatorio/**: relatório quarto no formato docx


## Atividades Avaliativas

### Avaliação 1

- **Tema:** Fundamentos de R e Manipulação de Dados
- **Data de entrega:** [14/05/2025]
- **Status:** [Concluído]
- **O que aprendi:** Este código ensina como importar, limpar e preparar dados de e-commerce em R. Você aprende a renomear colunas, 
converter tipos de dados e calcular estatísticas descritivas básicas. Além disso, demonstra como agrupar dados para analisar o 
faturamento por método de pagamento, o comportamento de clientes específicose o impacto de anúncios em vídeo nas conversões. 
Também explora o comportamento de diferentes tipos de clientes, incluindo taxas de devolução e faturamento médio.




## Anotações e Dicas Importantes

[Aqui você pode adicionar lembretes, dicas ou comandos úteis 
que aprendeu durante as aulas.]

*Para importar dados, use read_csv() do pacote readr. Certifique-se de que o caminho do arquivo esteja correto 
(você usou here::here() no seu código, o que é uma boa prática!).

*Use glimpse() do dplyr para ter uma visão geral rápida da estrutura dos seus dados, incluindo os tipos de cada coluna.

*A função rename() é útil para dar nomes mais intuitivos às suas variáveis.

*Esteja atento aos tipos de dados das suas colunas. Use as.factor(), as.numeric(), as.Date(), as.logical() conforme necessário para garantir que as análises sejam feitas corretamente.

*As funções select(), filter(), mutate(), group_by(), summarize() e arrange() do dplyr são ferramentas poderosas para manipular e analisar seus dados. Pratique o uso delas!

*O sistema de publicação Quarto permite criar relatórios dinâmicos e reproduzíveis combinando código (R, Python, etc.), texto e visualizações. Explore as diferentes opções de formatação que ele oferece.

*Utilize o Git e o GitHub para controlar as versões do seu projeto e colaborar com outras pessoas. Pratique os comandos básicos como git add, git commit e git push.

- Anotação ou dica 1:
Lembre-se dos seis passos da metodologia CRISP-DM: Entendimento do Negócio, 
Entendimento dos Dados, Preparação dos Dados, Modelagem, Avaliação e Implantação. 
Essa estrutura ajuda a organizar qualquer projeto de ciência de dados.

- Anotação ou dica 2
O operador pipe (%>%) do pacote dplyr torna o código mais legível ao encadear uma sequência de operações de manipulação de dados. 
Use-o sempre que possível para melhorar o fluxo do seu código.


# Glossário de Termos

Este glossário apresenta uma **versão inicial** dos termos relacionados 
às ferramentas, tecnologias e métodos que utilizaremos na disciplina de 
Introdução à Ciência de Dados: RStudio, R, Quarto, Markdown, 
Git e GitHub, Fundamentos de Probabilidade e Estatística.

> **IMPORTANTE**: Este é apenas um ponto de partida. Você deve 
assumir o protagonismo na ampliação e manutenção deste glossário, 
adicionando novos termos e conceitos à medida que avança no seu 
aprendizado. Anote definições de conceitos que encontrar durante as 
aulas e leituras, reescreva explicações com suas próprias palavras e 
personalize este recurso para que ele realmente apoie seu 
desenvolvimento na disciplina.

O glossário que você construir será uma ferramenta valiosa não apenas 
durante este semestre, mas também em seus futuros estudos e atividades 
profissionais. Consulte-o e, principalmente, enriqueça-o sempre que 
encontrar termos ou conceitos importantes.



## A 

**Ambiente de Desenvolvimento Integrado (IDE)**: Software que combina 
editor de código ou texto, console, gerenciamento de arquivos e outras 
ferramentas para facilitar o desenvolvimento de software.



## C 

**Cabeçalho YAML**: Seção no início de um documento Quarto, delimitada 
por três traços (---), onde são definidos metadados e opções de formatação 
para o documento.

**Células de Código** (*Code Chunks*): Blocos de código em um arquivo 
quarto que podem ser executados, gerando resultados que são incluídos 
no documento final.

**Chave-valor** (*key-value*): Formato de dados usado em YAML que 
associa um nome de propriedade (chave) a um conteúdo ou configuração 
específica (valor).

**Clone**: Cópia completa de um repositório, incluindo todos os arquivos, 
histórico e branches, para o computador local.

**Código Inline**: Código R incorporado diretamente no texto de um 
documento Quarto, indicado pela sintaxe `` `r ` ``, que é executado 
durante a renderização.

**Commit**: "Fotografia" do estado do projeto em um determinado 
momento feita pelo Git, com uma mensagem descritiva das alterações 
realizadas.

**Conflito**: Situação onde o Git não consegue mesclar automaticamente 
alterações de diferentes fontes porque ambas modificaram a mesma parte 
de um arquivo.

**Console**: Interface de linha de comando onde os códigos R são 
executados interativamente e os resultados são mostrados imediatamente.



## E 

**echo**: Opção de célula de código que controla se o código fonte 
é exibido (true) ou ocultado (false) no documento quarto final.

**Editor de texto/código**: Componente de um IDE onde você escreve e 
edita o código antes de executá-lo.

**eval**: Opção de célula de código que determina se o código deve 
ser executado (true) ou não (false) durante a renderização de 
um arquivo quarto.



## F 

**fig-cap**: Opção de célula de código que adiciona uma legenda a 
uma figura gerada pelo código em um arquivo quarto.

**Formato de Saída**: Tipo de documento final gerado pelo Quarto, 
como HTML, PDF, DOCX, apresentações, entre outros.



## G 

**Git**: Sistema de controle de versão distribuído que registra 
alterações em arquivos ao longo do tempo.

**Git Bash**: Terminal especial instalado com o Git no Windows que 
permite executar comandos Git e outros comandos Unix.

**GitHub**: Plataforma online que hospeda repositórios Git e oferece 
ferramentas adicionais para colaboração e desenvolvimento de projetos.



## H 

**Hash**: Identificador único (como `f7d2e09`) gerado para cada commit, 
permitindo referenciar versões específicas dos arquivos.



## I

**Indentação**: Espaçamento consistente utilizado no YAML para indicar 
hierarquia e aninhamento de opções, crucial para o funcionamento 
correto dos metadados.

**Issue**: Funcionalidade do GitHub para rastrear tarefas, melhorias, 
bugs e outras questões relacionadas a um projeto.



## K 

**knitr**: Pacote R responsável por executar o código R em documentos 
Quarto, transformando (ou renderizando) o arquivo .qmd em um arquivo 
markdown intermediário (.md).



## L 

**Linguagem de Marcação**: Sistema de anotações inseridas em um 
texto para definir como ele deve ser estruturado, formatado ou 
apresentado. Ao contrário das linguagens de programação que executam 
comandos, as linguagens de marcação utilizam tags ou comandos para 
identificar elementos do documento (como títulos, parágrafos, 
listas) sem se preocupar com a lógica computacional. Exemplos 
incluem HTML (para páginas web), XML (para dados estruturados), 
LaTeX (para documentos científicos) e Markdown (usada no Quarto 
para formatação simplificada de texto).



## M 

**Main**: Branch principal de um repositório Git (anteriormente 
chamado de "master").

**Markdown**: Linguagem de marcação leve usada para formatar textos 
nos documentos Quarto, permitindo cabeçalhos, listas, negrito, 
itálico, links, entre outros elementos.

**Metadados**: Informações sobre o documento (como título, autor, 
data, formato) definidas no cabeçalho YAML de um arquivo quarto.



## O 

**Origin**: Nome padrão dado ao repositório remoto (normalmente no 
GitHub) a partir do qual um repositório local foi clonado.



## P 

**Pacote**: Coleção de funções, dados e documentação que estende 
as funcionalidades da linguagem R.

**Painel** (*Pane*): Áreas da interface do RStudio que contêm 
diferentes ferramentas, como editor, console, ambiente, etc.

**Pandoc**: Ferramenta universal de conversão de documentos que 
o Quarto utiliza para transformar arquivos markdown em formatos 
finais como HTML, PDF e DOCX.

**Projeto RStudio**: Sistema que organiza arquivos relacionados a 
uma análise específica em uma estrutura coerente, facilitando a 
organização e reprodutibilidade.

**Pull**: Ação de baixar as alterações do repositório remoto (GitHub) 
para o repositório local, atualizando-o.

**Push**: Ação de enviar commits do repositório local para o 
repositório remoto (GitHub).

**Publicação Técnica e Científica**: Processo de criar e disseminar 
documentos com conteúdo acadêmico ou técnico, seguindo padrões 
estabelecidos de formatação e referenciação.



## Q 

**QMD**: Extensão de arquivo (.qmd) específica dos documentos Quarto, 
que contém texto em Markdown, células de código e metadados YAML.

**Quarto**: Sistema de publicação científica e técnica de código 
aberto que permite combinar código, texto narrativo, equações e 
visualizações em um único documento. Sucessor do R Markdown.



## R 

**R**: Linguagem de programação especializada em análise estatística e 
visualização de dados.

**Referência Cruzada**: Recurso que permite fazer referência a elementos 
como figuras, tabelas e seções em qualquer parte do documento usando 
identificadores únicos.

**Render**: Processo de transformar um arquivo Quarto (.qmd) em seu 
formato final (HTML, PDF, etc.), executando código e formatando o 
conteúdo conforme as especificações.

**Repositório**: Coleção de arquivos e pastas de um projeto, junto 
com o histórico completo de alterações.

**Repositório Local**: Versão do repositório armazenada no seu 
computador.

**Repositório Remoto**: Versão do repositório armazenada em um 
servidor (como o GitHub).

**Reprodutibilidade**: Princípio que permite que outros pesquisadores 
e profissionais possam replicar exatamente os mesmos resultados 
utilizando os mesmos dados e códigos. No contexto corporativo, garante 
a auditabilidade de análises, facilita a transferência de conhecimento 
entre equipes, permite verificação de resultados por diferentes 
stakeholders e assegura a continuidade de projetos mesmo com 
mudanças de pessoal.



## S 

**Stage/Staging Area**: Área intermediária onde as alterações são 
adicionadas (via `git add`) antes de serem definitivamente salvas 
em um commit.



## T 

**Terminal**: Interface de linha de comando onde os comandos Git 
são executados.

**TOC** (*Table of Contents*): Sumário ou índice automático gerado 
pelo Quarto com base na estrutura de títulos e subtítulos do documento.

**Typst**: Sistema moderno de tipografia utilizado pelo Quarto como 
alternativa ao LaTeX para produzir documentos PDF com alta qualidade 
tipográfica.



## W 

**warning**: Opção de célula de código que controla se os avisos 
gerados durante a execução do código são exibidos (true) ou ocultados 
(false) no documento quarto final.

**Working Directory**: Diretório local onde os arquivos do projeto 
estão sendo editados ativamente.



## Y 

**YAML** (*Yet Another Markup Language*): Linguagem de serialização 
de dados legível por humanos usada para os metadados de documentos 
Quarto, caracterizada pelo formato de pares chave-valor e indentação 
significativa.

**Data Manipulation and Analysis (R):**

*Data Frame:* A estrutura de dados fundamental em R para armazenar tabelas.

*Variável:* Uma característica ou atributo dos dados (coluna em um data frame).

*Observação:* Uma unidade de dados (linha em um data frame).

*Função:* Um bloco de código reutilizável que realiza uma tarefa específica.

*Argumento:* Valores passados para uma função para controlar seu comportamento.

*Tipo de Dados:* A classificação dos valores armazenados em uma variável (e.g., numérico, caractere, lógico, fator).

*Fator:* Um tipo de dado em R usado para representar variáveis categóricas com níveis.

*tidyverse:* Um conjunto de pacotes R, incluindo dplyr e readr, que compartilham uma filosofia de design consistente para manipulação e visualização de dados.

*readr:* Pacote do tidyverse usado para importar dados (como arquivos CSV).

*ggplot2:* Um pacote do tidyverse para criar gráficos e visualizações de dados.

*Visualização de Dados:* A representação gráfica de dados para identificar padrões e insights.

**Statistics and Probability:**

*População: O conjunto completo de itens ou indivíduos sobre os quais se deseja obter informações.

*Amostra: Um subconjunto da população usado para inferir informações sobre a população inteira.

*Média: Uma medida de tendência central (o valor médio).

*Mediana: Outra medida de tendência central (o valor do meio quando os dados são ordenados).

*Moda: O valor que ocorre com maior frequência em um conjunto de dados.

*Desvio Padrão: Uma medida da dispersão dos dados em torno da média.

*Variância: O quadrado do desvio padrão, também uma medida de dispersão.

*Distribuição de Probabilidade: Uma função que descreve a probabilidade de diferentes resultados possíveis em um experimento aleatório.

*Inferência Estatística: O processo de usar dados de uma amostra para tirar conclusões sobre uma população maior.

*Hipótese Nula: Uma afirmação inicial que se tenta refutar através da análise de dados.

*Hipótese Alternativa: A afirmação que se espera encontrar evidências para apoiar.

*Valor-p (p-value): A probabilidade de obter resultados tão extremos (ou mais extremos) quanto os observados, assumindo que a hipótese nula seja verdadeira.

**General Data Science Concepts:**

*Dados Brutos: Dados em seu formato original, antes de serem processados ou limpos.

*Limpeza de Dados: O processo de identificar e corrigir erros, inconsistências e imprecisões nos dados.

*Preparação de Dados: O processo de transformar e organizar os dados para análise.

*Análise Exploratória de Dados (EDA): O processo de explorar e resumir os dados para entender seus principais padrões e características.

**Outros:**

*API (Interface de Programação de Aplicações): Um conjunto de regras e protocolos que permite que diferentes softwares se comuniquem entre si.

**testes de significancia**

COLOCAR NA PROVA

$$
\begin{cases}
H_0: p = 0.50 \\
H_A: p \neq 0.50
\end{cases}
$$

**Funções do Pacote pwr.**

*Função	Descrição
*pwr.p.test	teste de proporção para uma amostra
*pwr.2p.test	teste de proporção para duas amostras
*pwr.2p2n.test	teste de proporção para duas amostras (tamanhos desiguais)
*pwr.t.test	testes t para duas amostras, uma amostra e amostras pareadas
*pwr.t2n.test	teste t para duas amostras (tamanhos desiguais)
*pwr.anova.test	ANOVA balanceada de um fator
*pwr.r.test	teste de correlação
*pwr.chisq.test	teste qui-quadrado (ajuste de distribuição e associação)
*pwr.f2.test	teste para o modelo linear geral

Como Escrever Hipóteses com LaTeX?
Escrevendo Hipóteses em LaTeX

Em alguns exercícios, você precisará escrever as hipóteses nula (H0
) e alternativa (HA
).

Você pode fazer isso facilmente com LaTeX, a melhor linguagem para escrever matemática, na verdade, é a melhora linguagem para escrever qualquer coisa que precise de formatação.

Modelo Básico:
$$
\begin{cases}
H_0: p_1 = p_2 \\
H_A: p_1 > p_2
\end{cases}
$$

produz:

{H0:p1=p2HA:p1>p2

$$ ... $$ → abre uma equação centralizada
\begin{cases} ... \end{cases} → cria um bloco alinhado de hipóteses
H_0, H_A → índices usando underline _
p_1, p_2, \mu_1, \mu_2 → parâmetros como proporções ou médias
Sinais Matemáticos Úteis no LaTeX:
Símbolo	Código LaTeX	Significado	Exemplo
=	=	Igual	H_0: p_1 = p_2
≠	\neq	Diferente	H_A: p_1 \neq p_2
>	>	Maior	H_A: \mu_1 > \mu_2
<	<	Menor	H_A: p_1 < p_2
≥	\geq	Maior ou igual	H_0: p_B \geq p_A
≤	\leq	Menor ou igual	H_0: \mu_1 \leq \mu_2
Exemplo com \leq:
$$
\begin{cases}
H_0: p_B \leq p_A \\
H_A: p_B > p_A
\end{cases}
$$

produz:

{H0:pB≤pAHA:pB>pA

Esse tipo de hipótese é comum quando queremos mostrar melhoria ou aumento em relação a uma condição atual.

Você pode copiar e adaptar esses modelos nos exercícios!