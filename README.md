# DataCity
### Ciência de Dados Aplicada à Mobilidade Urbana

**Python | MongoDB | Pandas | NumPy | Matplotlib | Análise Exploratória de Dados**

---

## 📌 1. Apresentação

O **DataCity — Ciência de Dados Aplicada à Mobilidade Urbana** é um projeto acadêmico desenvolvido com o objetivo de demonstrar, de maneira prática, a aplicação dos principais conceitos, técnicas e ferramentas de Ciência de Dados na investigação de problemas relacionados à mobilidade urbana.

A proposta consiste no desenvolvimento de uma aplicação utilizando a linguagem **Python e seu ecossistema de bibliotecas especializadas**, integrada ao banco de dados não relacional **MongoDB**, para realizar operações de armazenamento, recuperação, tratamento, processamento, análise e visualização de dados.

O projeto utiliza como cenário a cidade fictícia de **Nova Esperança**, que possui aproximadamente 750 mil habitantes e enfrenta desafios relacionados à eficiência do transporte coletivo, pontualidade dos ônibus, distribuição da frota, demanda de passageiros e ocorrências operacionais.

A partir de registros sintéticos que representam o funcionamento do transporte público, o DataCity busca transformar dados operacionais em informações e conhecimentos capazes de subsidiar análises e decisões fundamentadas.

Mais do que desenvolver uma aplicação computacional, o projeto pretende demonstrar como diferentes tecnologias podem trabalhar de maneira integrada na construção de soluções orientadas por dados.

## 🎯 2. Objetivos do projeto

### Objetivo geral

Desenvolver uma aplicação de Ciência de Dados capaz de armazenar, recuperar, processar, analisar e visualizar informações relacionadas à mobilidade urbana, utilizando Python, MongoDB e bibliotecas especializadas, com o propósito de identificar padrões, produzir indicadores e apoiar a compreensão de problemas associados ao transporte coletivo.

### Objetivos específicos

- Aplicar os fundamentos de Ciência de Dados em um cenário prático e contextualizado.
- Desenvolver uma aplicação Python com arquitetura modular.
- Implementar a conectividade entre Python e MongoDB utilizando PyMongo.
- Trabalhar com modelagem, armazenamento e consultas em bancos de dados NoSQL orientados a documentos.
- Utilizar grandes conjuntos de dados sintéticos para simular operações de mobilidade urbana.
- Aplicar técnicas de preparação, limpeza, padronização e transformação de dados.
- Utilizar Pandas e NumPy para manipulação e análise de informações.
- Desenvolver análises exploratórias utilizando conceitos de estatística descritiva.
- Construir gráficos e visualizações com Matplotlib e, futuramente, Seaborn.
- Produzir indicadores relacionados à demanda, pontualidade, duração das viagens e ocorrências.
- Explorar técnicas introdutórias de Machine Learning em etapas futuras.
- Desenvolver habilidades de interpretação crítica e comunicação de resultados analíticos.

## 🏙️ 3. Contextualização: o problema da mobilidade urbana

A mobilidade urbana representa um dos principais desafios enfrentados por cidades de médio e grande porte.

O crescimento populacional, a expansão territorial, o aumento da circulação de veículos e a necessidade de oferecer serviços de transporte eficientes exigem planejamento e utilização adequada dos recursos disponíveis.

Nesse contexto, sistemas de transporte coletivo produzem diariamente uma quantidade significativa de dados relacionados a viagens, passageiros, horários, veículos, itinerários e ocorrências.

Entretanto, a simples existência desses registros não garante a produção de informações relevantes.

É necessário desenvolver mecanismos capazes de organizar, processar e interpretar os dados, permitindo identificar padrões e compreender o comportamento do sistema.

O DataCity foi concebido justamente para explorar esse processo.

### Cenário de estudo: Nova Esperança

A cidade fictícia de Nova Esperança apresenta desafios como:

- Atrasos recorrentes em determinadas linhas de ônibus.
- Diferenças na demanda de passageiros entre regiões.
- Variações na duração das viagens conforme horários e condições operacionais.
- Ocorrências que afetam a regularidade do transporte.
- Necessidade de compreender a distribuição da frota.
- Dificuldades na identificação de padrões e tendências a partir dos registros disponíveis.

O projeto busca investigar essas questões utilizando técnicas de Ciência de Dados.

**Importante:** todos os dados utilizados são fictícios e gerados para fins acadêmicos. Os resultados obtidos não representam estatísticas reais de municípios ou sistemas de transporte.

## 🧠 4. Fundamentos de Ciência de Dados

O DataCity utiliza uma abordagem baseada no ciclo de vida dos dados, compreendendo as seguintes etapas:

**1. Coleta e obtenção:** identificação e recuperação de registros relacionados à operação do transporte coletivo.

**2. Armazenamento:** organização dos registros em coleções documentais no MongoDB.

**3. Preparação:** identificação e tratamento de inconsistências, valores ausentes, duplicidades e diferenças de padronização.

**4. Processamento:** utilização de bibliotecas Python para manipulação e transformação dos conjuntos de dados.

**5. Análise exploratória:** aplicação de estatísticas descritivas, agrupamentos e investigação de relações entre variáveis.

**6. Visualização:** construção de gráficos e representações que facilitem a interpretação dos resultados.

**7. Interpretação e tomada de decisão:** identificação de padrões, elaboração de conclusões e formulação de recomendações fundamentadas.

### A Pirâmide DIKW no DataCity

O projeto também demonstra a aplicação do modelo DIKW:

| Nível | Aplicação prática |
|---|---|
| Dados | Uma viagem apresentou 18 minutos de atraso. |
| Informação | Determinada linha registrou atraso médio de 12 minutos. |
| Conhecimento | Os atrasos são mais frequentes nos horários de pico. |
| Sabedoria | Investigar as causas e avaliar possíveis ajustes operacionais. |

Essa abordagem reforça um princípio fundamental: **dados, isoladamente, não representam conhecimento. É necessário processá-los, contextualizá-los e interpretá-los.**

## 🛠️ 5. Tecnologias utilizadas

O projeto utiliza ou prevê a utilização das seguintes tecnologias:

| Tecnologia | Aplicação |
|---|---|
| Python | Linguagem principal da aplicação. |
| MongoDB | Armazenamento e gerenciamento dos dados não relacionais. |
| PyMongo | Conectividade entre Python e MongoDB. |
| Pandas | Manipulação, preparação e análise de dados. |
| NumPy | Processamento e operações numéricas. |
| Matplotlib | Construção de gráficos e visualizações. |
| Seaborn | Visualizações estatísticas complementares. |
| Scikit-learn | Introdução a modelos de Machine Learning. |
| SciPy | Métodos estatísticos e computação científica. |
| Jupyter Notebook | Execução e documentação de análises interativas. |
| Google Colab | Ambiente alternativo para experimentação e atividades acadêmicas. |
| Git e GitHub | Versionamento, documentação e organização do projeto. |

**Observação:** algumas tecnologias representam possibilidades de evolução e poderão ser incorporadas progressivamente.

## 🏗️ 6. Arquitetura da aplicação

O DataCity adota uma arquitetura modular, com separação das responsabilidades de armazenamento, acesso aos dados, processamento, análise e visualização.

O fluxo principal está organizado da seguinte maneira:

```text
                  DATACITY
                     |
                     v
              BANCO DE DADOS
                  MongoDB
                     |
                     v
                  PyMongo
            Conexão e consultas
                     |
                     v
                   Python
             Processamento geral
                     |
          +----------+----------+
          |          |          |
          v          v          v
        Pandas      NumPy    Estatística
       Tratamento  Cálculos    Análise
          |          |          |
          +----------+----------+
                     |
                     v
             ANÁLISE EXPLORATÓRIA
                     |
                     v
            Matplotlib / Seaborn
                     |
                     v
           INDICADORES E GRÁFICOS
                     |
                     v
           INTERPRETAÇÃO DOS DADOS
                     |
                     v
            APOIO ÀS DECISÕES
```

A arquitetura foi concebida para permitir a evolução independente dos componentes e facilitar a reutilização dos módulos em diferentes atividades acadêmicas.

## 🗄️ 7. Estrutura do banco de dados

O DataCity utiliza um banco de dados MongoDB denominado:

`datacity_db`

A modelagem inicial é composta por cinco coleções principais.

### Coleção `regioes`

Armazena informações relacionadas às regiões e aos setores territoriais da cidade.

**Principais atributos:**
- Identificador da região.
- Nome e descrição.
- Zona da cidade.
- Localização geográfica.
- População estimada.
- Área territorial.

### Coleção `linhas`

Armazena informações das linhas de transporte coletivo.

**Principais atributos:**
- Identificador e código da linha.
- Nome.
- Região associada.
- Extensão.
- Situação operacional.

### Coleção `veiculos`

Armazena informações dos ônibus utilizados na operação.

**Principais atributos:**
- Identificador e prefixo do veículo.
- Modelo e ano.
- Capacidade de passageiros.
- Tipo de combustível.
- Linha associada.
- Situação operacional.

### Coleção `viagens`

Armazena os registros operacionais das viagens realizadas.

**Principais atributos:**
- Identificador da viagem.
- Linha e veículo associados.
- Região.
- Data e horários.
- Duração prevista e realizada.
- Quantidade de passageiros.
- Atraso registrado.
- Avaliação média.
- Ocorrência associada, quando existente.
- Situação da viagem.

### Coleção `ocorrencias`

Armazena eventos que podem afetar o funcionamento do transporte coletivo.

**Principais atributos:**
- Identificador da ocorrência.
- Tipo e descrição.
- Nível de impacto.
- Data e horário.
- Localização geográfica.
- Linha e viagem associadas.
- Situação da ocorrência.

### Relacionamentos lógicos

Embora o MongoDB não utilize obrigatoriamente relacionamentos por chaves estrangeiras como os bancos relacionais, o DataCity estabelece associações entre documentos por meio de identificadores.

Essas referências permitem relacionar viagens, linhas, veículos, regiões e ocorrências durante as consultas e análises.

## 📊 8. Base de dados para experimentação

Para permitir análises com volumes significativos de registros, foi preparada uma base sintética contendo **181.500 documentos**, distribuídos entre as coleções:

| Coleção | Documentos |
|---|---:|
| Regiões | 300 |
| Linhas | 1.200 |
| Veículos | 5.000 |
| Viagens | 150.000 |
| Ocorrências | 25.000 |
| **Total** | **181.500** |

Os registros foram gerados para possibilitar exercícios de armazenamento, consultas, agregações, tratamento, análise exploratória e avaliação de desempenho.

O volume de dados é intencionalmente ampliado para atender aos objetivos acadêmicos do projeto e não representa a dimensão real de uma rede de transporte coletivo.

**A existência de um volume elevado de documentos não caracteriza, isoladamente, uma aplicação de Big Data.** A classificação depende também de fatores como velocidade, variedade, infraestrutura e complexidade do processamento.

## 🔍 9. Funcionalidades previstas

O DataCity será desenvolvido progressivamente, contemplando os seguintes grupos de funcionalidades.

### 9.1. Conectividade com MongoDB

- Estabelecimento de conexão com o banco de dados.
- Seleção de coleções.
- Recuperação de documentos.
- Consultas com filtros.
- Projeção de atributos.
- Ordenação e limitação de resultados.
- Utilização de pipelines de agregação.

### 9.2. Preparação e tratamento dos dados

- Conversão de documentos MongoDB para DataFrames.
- Identificação de valores ausentes.
- Identificação de duplicidades.
- Padronização de atributos.
- Conversão de tipos de dados.
- Investigação de registros inconsistentes.

### 9.3. Análise exploratória

- Estatísticas descritivas.
- Médias, medianas, valores máximos e mínimos.
- Distribuições de frequência.
- Agrupamentos por linha, região e período.
- Análise de correlações.
- Identificação de padrões e valores extremos.

### 9.4. Indicadores de mobilidade urbana

- Atraso médio por linha.
- Taxa de pontualidade.
- Quantidade de passageiros por região.
- Duração média das viagens.
- Frequência de ocorrências.
- Avaliação média das viagens.
- Distribuição dos registros por período.

### 9.5. Visualização de dados

- Gráficos de barras.
- Gráficos de linhas.
- Histogramas.
- Gráficos de dispersão.
- Visualizações estatísticas complementares.

### 9.6. Relatórios

- Apresentação de indicadores.
- Exportação de dados processados.
- Geração de gráficos.
- Documentação das análises.
- Interpretação dos resultados.

## 🧪 10. Exemplos de análises

Entre as questões investigadas pelo DataCity, destacam-se:

**Pontualidade:** quais linhas apresentam maiores atrasos médios? Existem diferenças entre horários e regiões?

**Demanda:** quais regiões concentram maior quantidade de passageiros registrados? Como essa demanda varia ao longo do tempo?

**Eficiência:** quais viagens apresentam maior duração? Existe associação entre quantidade de passageiros e duração?

**Ocorrências:** quais tipos de eventos aparecem com maior frequência? Como se relacionam com os atrasos registrados?

**Qualidade:** como se comportam as avaliações médias das viagens? Existem diferenças entre linhas e regiões?

As respostas serão obtidas por meio de consultas, cálculos estatísticos, visualizações e interpretação dos dados.

## 📁 11. Organização prevista do projeto

A aplicação poderá utilizar a seguinte estrutura modular:

```text
DataCity/
│
├── main.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
│
├── config/
│   └── database.py
│
├── repositories/
│   ├── linhas_repository.py
│   ├── veiculos_repository.py
│   ├── viagens_repository.py
│   ├── ocorrencias_repository.py
│   └── regioes_repository.py
│
├── services/
│   ├── preparacao_dados.py
│   ├── analise_exploratoria.py
│   └── indicadores.py
│
├── visualizations/
│   └── graficos.py
│
├── scripts/
│   └── popular_banco.py
│
├── notebooks/
│   └── analise_datacity.ipynb
│
├── data/
│   └── samples/
│
├── reports/
│
└── docs/
```

Essa estrutura representa a organização planejada da aplicação e poderá ser ajustada conforme sua evolução.

## 🚀 12. Instalação e execução

**Pré-requisitos:**
- Python 3.
- MongoDB Community Server ou MongoDB Atlas.
- Git.
- Bibliotecas Python utilizadas pelo projeto.

### 12.1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/DataCity.git
cd DataCity
```

Substitua `SEU-USUARIO` pelo usuário responsável pelo repositório.

### 12.2. Criar o ambiente virtual

```bash
python -m venv .venv
```

Ativação no Windows:

```bash
.venv\Scripts\activate
```

Ativação no Linux ou macOS:

```bash
source .venv/bin/activate
```

### 12.3. Instalar as dependências

Após a disponibilização do arquivo `requirements.txt`:

```bash
python -m pip install -r requirements.txt
```

### 12.4. Configurar a conexão

Crie um arquivo `.env` a partir de `.env.example` e configure a variável:

```env
MONGODB_URI=mongodb://localhost:27017/
```

Para utilização do MongoDB Atlas, configure a URI fornecida pela instância correspondente.

**Nunca publique credenciais, senhas ou arquivos `.env` contendo informações sensíveis.**

### 12.5. Executar a aplicação

Quando o módulo principal estiver implementado:

```bash
python main.py
```

As instruções de execução serão atualizadas conforme os componentes forem disponibilizados.

## 🔐 13. Segurança e boas práticas

O projeto busca incorporar boas práticas de desenvolvimento e manipulação de dados.

Entre elas:

- Utilização de variáveis de ambiente para configurações sensíveis.
- Separação entre acesso ao banco e processamento analítico.
- Tratamento de exceções.
- Validação de dados.
- Utilização de consultas e projeções adequadas.
- Criação de índices conforme a necessidade.
- Documentação dos procedimentos.
- Versionamento do código-fonte.
- Utilização de dados sintéticos para atividades acadêmicas.

A aplicação também permitirá discutir conceitos de qualidade, governança e responsabilidade no tratamento dos dados.

## 🎓 14. Finalidade acadêmica

O DataCity foi concebido como um **ativo acadêmico reutilizável**, destinado ao ensino, à experimentação e à demonstração prática de conceitos de Ciência de Dados.

O projeto poderá ser utilizado em aulas, atividades práticas, estudos de caso, projetos integradores e demonstrações técnicas.

Sua proposta pedagógica é permitir que os estudantes compreendam o fluxo completo de trabalho com dados, desde o armazenamento até a interpretação dos resultados.

O foco não está apenas em executar códigos Python, mas em compreender:

- Qual problema está sendo investigado.
- Quais dados são necessários.
- Como os dados estão organizados.
- Como recuperá-los e prepará-los.
- Quais técnicas analíticas são adequadas.
- Como interpretar os indicadores.
- Quais limitações existem nas análises.
- Como comunicar conclusões fundamentadas.

**O código é o instrumento. A compreensão do problema e a interpretação dos dados são os elementos centrais da aprendizagem.**

## 🗺️ 15. Roadmap de desenvolvimento

O DataCity será desenvolvido de maneira incremental.

- [x] Definição do cenário e dos objetivos do projeto.
- [x] Definição da arquitetura conceitual.
- [x] Modelagem inicial das coleções MongoDB.
- [x] Geração da base sintética com 181.500 documentos.
- [x] Elaboração dos materiais didáticos de referência.
- [ ] Estruturação dos diretórios e módulos Python.
- [ ] Configuração e validação da conexão com MongoDB.
- [ ] Implementação dos repositórios de acesso aos dados.
- [ ] Desenvolvimento dos serviços de preparação.
- [ ] Implementação das análises exploratórias.
- [ ] Construção dos indicadores de mobilidade.
- [ ] Desenvolvimento das visualizações.
- [ ] Criação dos notebooks analíticos.
- [ ] Implementação de relatórios e exportações.
- [ ] Avaliação de desempenho das consultas.
- [ ] Exploração de técnicas introdutórias de Machine Learning.
- [ ] Documentação e consolidação da versão funcional.

**Status:** projeto acadêmico em desenvolvimento.

## 📚 16. Referências e documentação

As seguintes referências poderão apoiar o desenvolvimento e o aprofundamento dos conceitos:

- [Documentação oficial do Python](https://docs.python.org/3/)
- [Documentação oficial do MongoDB](https://www.mongodb.com/docs/)
- [Documentação oficial do PyMongo](https://pymongo.readthedocs.io/)
- [Documentação oficial do Pandas](https://pandas.pydata.org/docs/)
- [Documentação oficial do NumPy](https://numpy.org/doc/)
- [Documentação oficial do Matplotlib](https://matplotlib.org/stable/)
- [Documentação oficial do Scikit-learn](https://scikit-learn.org/stable/)

**Bibliografia complementar:**

- GRUS, Joel. *Data Science do Zero*.
- MCKINNEY, Wes. *Python para Análise de Dados*.
- PROVOST, Foster; FAWCETT, Tom. *Data Science para Negócios*.
- VANDERPLAS, Jake. *Python Data Science Handbook*.

## 👨‍🏫 17. Autor e desenvolvimento

**Prof. André Olímpio**

Professor e profissional da área de Tecnologia da Informação, com atuação no ensino técnico, na graduação, na pós-graduação e na educação a distância.

O DataCity integra um conjunto de projetos acadêmicos voltados à aplicação prática de conceitos de programação, bancos de dados, desenvolvimento de sistemas e Ciência de Dados.

O projeto é desenvolvido com finalidade educacional, buscando aproximar a fundamentação teórica das práticas utilizadas no desenvolvimento de soluções computacionais.

**GitHub:** [andreolimpio](https://github.com/andreolimpio)

**LinkedIn:** [André Olímpio](https://www.linkedin.com/in/andreolimpio/)

---

## Considerações finais

O **DataCity — Ciência de Dados Aplicada à Mobilidade Urbana** representa uma proposta de integração entre tecnologia, análise de dados e resolução de problemas.

Ao utilizar Python, MongoDB e bibliotecas especializadas, o projeto demonstra como diferentes componentes tecnológicos podem ser organizados para transformar registros operacionais em informações relevantes.

Sua evolução permitirá explorar conceitos de modelagem, armazenamento, consultas, processamento, estatística, visualização e análise preditiva, sempre considerando a importância da interpretação crítica dos resultados.

Mais do que construir uma aplicação funcional, o DataCity pretende contribuir para o desenvolvimento de competências técnicas e analíticas essenciais à formação de profissionais de Tecnologia da Informação e Ciência de Dados.

**DataCity — Transformando dados em conhecimento para compreender a mobilidade urbana.**

---

*Projeto acadêmico desenvolvido para fins educacionais. Dados e cenários utilizados são fictícios.*
