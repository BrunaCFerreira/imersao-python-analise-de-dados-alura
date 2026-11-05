# Imersão Python: Análise de Dados | Alura

Este repositório reúne as atividades que desenvolvi durante a **Imersão Python: Análise de Dados da Alura**, realizada ao longo de três dias.

A proposta foi aprender e colocar em prática diferentes etapas de uma análise de dados, desde a importação, organização e tratamento das informações até a construção de gráficos, interpretação dos resultados e introdução à modelagem preditiva.

Durante a imersão, trabalhei com planilhas Excel, dados do mercado financeiro e bibliotecas Python voltadas à análise e visualização de dados. Também tive meu primeiro contato com o **Prophet**, utilizado para criar previsões de séries temporais a partir de dados históricos.

Os exercícios foram desenvolvidos acompanhando as aulas da Alura, e cada notebook corresponde ao conteúdo trabalhado em um dos três dias.

## 📚 O que foi desenvolvido?

### Dia 1 — Análise de dados com Pandas

No primeiro dia, trabalhei com uma planilha Excel para aprender a importar, explorar, organizar e tratar dados utilizando Python e Pandas.

Também pratiquei a combinação de informações de diferentes tabelas, cálculos, agrupamentos e a construção de gráficos para visualizar os resultados da análise.

**Arquivo:** `01_analise_com_pandas.ipynb`

### Dia 2 — Visualização de dados financeiros

No segundo dia, utilizei a biblioteca `yfinance` para obter dados históricos de ações e explorar diferentes maneiras de representá-los visualmente.

Trabalhei com Matplotlib, Plotly e mplfinance, incluindo a construção de gráficos de candlestick e visualizações interativas.

**Arquivo:** `02_visualizacao_financeira.ipynb`

### Dia 3 — Previsão de séries temporais

No terceiro dia, conheci o Prophet, uma ferramenta de modelagem e previsão de séries temporais.

A atividade envolveu preparar os dados, separar períodos para treinamento e teste, ajustar um modelo e visualizar previsões em comparação com os dados históricos.

Foi uma introdução prática à análise preditiva, uma área que também se relaciona com aplicações de inteligência artificial e aprendizado de máquina.

**Arquivo:** `03_previsao_com_prophet.ipynb`

## 💭 Sobre as minhas anotações

Uma observação antes de abrir os notebooks: vocês vão encontrar alguns comentários meus escritos de maneira mais informal.

Enquanto acompanhava as aulas, eu costumava anotar o que estava entendendo, as explicações que achava importantes e algumas coisas que ia percebendo conforme executava os códigos.

Essas observações não foram escritas pensando em uma publicação no GitHub. Eram simplesmente minhas anotações de estudo, feitas naquele momento para me ajudar a compreender e lembrar o que estava aprendendo.

Quando decidi organizar os arquivos para publicar, pensei em retirar esses comentários ou reescrevê-los de maneira mais formal. Mas acabei escolhendo mantê-los.

Afinal, eles fazem parte do meu processo de aprendizado e também carregam um pouco da minha personalidade. Fiz alguns ajustes de clareza e correções técnicas, mas preferi preservar a espontaneidade das anotações.

Então, além dos códigos e gráficos, vocês também terão acesso a alguns dos meus pensamentos e observações durante a imersão. :)

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem utilizada nas atividades.
- **Pandas:** manipulação, tratamento e análise de dados.
- **Excel e OpenPyXL:** leitura e utilização de planilhas.
- **Matplotlib:** construção de gráficos.
- **Plotly:** visualizações de dados, incluindo gráficos interativos.
- **mplfinance:** gráficos financeiros e candlesticks.
- **yfinance:** obtenção de dados históricos do mercado financeiro.
- **Prophet:** modelagem e previsão de séries temporais.
- **Jupyter Notebook / Google Colab / VS Code:** ambientes para desenvolvimento e execução.

## 💻 Como visualizar ou executar o projeto

### Apenas visualizar no GitHub

Se você quer somente conhecer o projeto, **não precisa instalar nada**.

Basta abrir os arquivos `.ipynb` diretamente neste repositório para visualizar os códigos, minhas anotações e os resultados que estiverem salvos nos notebooks.

**Observação:** algumas visualizações interativas do Plotly podem não ser exibidas diretamente pelo GitHub, mesmo funcionando normalmente no VS Code ou no Google Colab.

### Baixar e executar no computador

Se você quiser baixar os notebooks e executar os códigos, será necessário ter o **Python instalado**, além das bibliotecas utilizadas no projeto.

Para facilitar, incluí o arquivo `requirements.txt`, que vem trazendo todas as bibliotecas necessárias.

**1. Baixe o repositório**

Na página do GitHub, clique em `Code` → `Download ZIP`, extraia os arquivos e abra a pasta principal do projeto no VS Code.

**2. Crie um ambiente virtual (recomendado)**

No terminal do VS Code, dentro da pasta principal do projeto, execute:

```powershell
python -m venv .venv
```

**3. Instale as bibliotecas**

No Windows, execute:

```powershell
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

Esse comando instala as dependências listadas no arquivo `requirements.txt` dentro do ambiente virtual.

Se você já estiver utilizando outro ambiente Python configurado, também poderá executar:

```powershell
python -m pip install -r requirements.txt
```

**4. Selecione o ambiente Python**

Abra um dos notebooks e, no canto superior direito do VS Code, clique em `Selecionar Kernel`.

Escolha o ambiente em que as bibliotecas foram instaladas. Se criou o `.venv`, selecione o Python correspondente a ele.

**5. Execute as células**

Execute as células na sequência em que aparecem no notebook.

No primeiro dia, os dados utilizados estão na planilha `content/Atividade prática Alura.xlsx`, incluída no repositório. Para que o caminho relativo funcione, execute o notebook com a pasta principal do projeto como diretório de trabalho.

Os notebooks dos dias 2 e 3 utilizam dados obtidos pela internet, portanto precisam de conexão para realizar novas consultas.

### E se aparecer algum erro?

Se surgir uma mensagem como:

```text
ModuleNotFoundError: No module named 'pandas'
```

provavelmente a biblioteca não está instalada no ambiente Python que está executando o notebook.

Confira se a instalação do `requirements.txt` foi concluída e se o kernel selecionado no VS Code corresponde ao ambiente correto.

Dependendo da versão do Python e das bibliotecas, podem ser necessários ajustes de compatibilidade.

## 📁 Estrutura do repositório

```text
imersao-python-analise-de-dados-alura/
├── README.md
├── requirements.txt
├── 01_analise_com_pandas.ipynb
├── 02_visualizacao_financeira.ipynb
├── 03_previsao_com_prophet.ipynb
└── content/
    └── Atividade prática Alura.xlsx
```

## 📌 Créditos

As atividades foram desenvolvidas durante a **Imersão Python: Análise de Dados da Alura**, com exercícios guiados pelas aulas e minhas próprias anotações e experiências durante o aprendizado.

Este repositório tem finalidade educacional e registra minha prática com ferramentas de análise, visualização e previsão de dados.
