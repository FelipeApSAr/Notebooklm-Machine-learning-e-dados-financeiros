# Notebooklm: Machine learning e dados financeiros
O propósito desse repositório é descrever o uso da ferramenta NotebookLm do Google no processo de busca de fontes e na criação de um guia de estudos. O tema escolhido está na interface do uso de machine learning, LLM's e SLM's e no uso de aprendizagem estatística em geral para o estudo de dados ligados ao mercado financeiro.

## Objetivos
- Compreender melhor os principais conceitos relacionados com a criação de ferramentas de inteligência artificial
- Aplicar na prática a inteligência artificial no processo de busca de fontes
- Criar um miniguia de estudos baseado nas fontes coletadas
- Desenvolver alguns prompts que tragam informações interessantes e que possam ser reutilizados em outros diversos contextos.

## Busca de fontes
O processo de busca de fontes partiu de um conhecimento breve prévio do autor. A partir disso, foi possível utilizar ferramentas de IA (ChatGPT, Gemini) na busca de outras fontes semelhantes àquelas fornecidas e com o direcionamento desejado para o projeto. Também busquei por vídeos e conteúdos que sumarizem o processo básico de criação de modelos de aprendizagem estatística em Python.

### Fontes em vídeo:
**LLMs Explained: Tokens, Embeddings, Transformers and More** - Canal Syntax - https://youtu.be/YmLp8qe87A0<br>
**I Tried to Build an AI From Scratch** - Canal commonLuke - https://youtu.be/IoM5zUI8oFc<br>
**I Built an LLM from Scratch** - Canal Green Code - https://youtu.be/s9w3gtgvNSU<br>
**Let's build GPT: from scratch, in code, spelled out.** - Canal Andrej Karpathy - https://youtu.be/kCc8FmEb1nY<br>
**Create a Large Language Model from Scratch with Python – Tutorial** - Canal freeCodeCamp.org - https://youtu.be/UU1WVnMk4E8<br>
**PyTorch for Deep Learning & Machine Learning – Full Course** - Canal freeCodeCamp.org - https://youtu.be/V_xro1bcAuA<br>
**Transformers, the tech behind LLMs | Deep Learning Chapter 5** - Canal 3Blue1Brown - https://youtu.be/wjZofJX0v4M<br>
**Attention in transformers, step-by-step | Deep Learning Chapter 6** - Canal 3Blue1Brown - https://youtu.be/eMlx5fFNoYc<br>

### Fontes em PDF
**Build a Large Language Model** - Sebastian Raschka<br>
**Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics, and Speech Recognition with Language Models** - Daniel Jurafsky e James H. Martin<br>
**Financial Machine Learning** - Bryan T. Kelly e Dacheng Xiu<br>
**Machine Learning in Finance from theory to practice** - Matthew F. Dixon, Igor Halperin, e Paul Bilokon<br>
**Signature Methods in Finance** - Christian Bayer, Gonçalo dos Reis, Blanka Horvath e Harald Oberhauser<br>
**Data Science for Economics and Finance Methodologies and Applications** - Sergio Consoli, Diego Reforgiato Recupero, e Michaela Saisana<br>
**An introduction to statistical learning with applications in python** - Gareth James, Daniela Witten, Trevor Hastie, Robert Tibshirani e Jonathan Taylor<br>

### Fontes em sites
**Deep Learning an MIT press book** - https://www.deeplearningbook.org/ - Ian Goodfellow and Yoshua Bengio and Aaron Courville<br>
**A dive into deep learning** - https://d2l.ai/ - Aston Zhang, Zack C. Lipton, Mu Li, Alex J. Smola entre outros<br>
**Machine learning for trading** - https://github.com/stefan-jansen/machine-learning-for-trading - Stefan Jansen - Apresenta algoritmos de trading utilizando machine learning<br>
**Tidy finance** - https://www.tidy-finance.org/ - Christoph Frey, Christoph Scheuch, Stefan Voigt e Patrick Weiss - Livro e pacote de análise em Python<br>

### Fontes extras
Utilizando a ferramenta de pesquisa do próprio NotebookLm, foi possível angariar outras diversas fontes apresentadas abaixo. As fontes estão ligadas com os tópicos acima: machine learning, LLMs e como utilizar isso em dados financeiros

**A Review of Large Language Models for Stock Price Forecasting from a Hedge-Fund Perspective** - https://arxiv.org/pdf/2605.05211 - Olivia Zhang e Zhilin Zhang<br>
**The New Quant: A Survey of Large Language Models in Financial Prediction and Trading** - https://arxiv.org/pdf/2510.05533 - Weilong Fu<br>
**TOWARDS EXPERT FINANCIAL QA VIA SELF-IMPROVING RAG** - https://arxiv.org/pdf/2608.26706 - Junjie Xiong, Shawheen Ghezavat e Aum Hirpara<br>
**TradingAgents: Multi-Agents LLM Financial Trading Framework** - https://arxiv.org/pdf/2412.20138 - Yijia Xiao, Edward Sun, Di Luo, Wei Wang <br>
**Large Language Models for Financial Aid in Financial Time-series Forecasting** - https://arxiv.org/pdf/2410.19025 - Md Khairul Islam, Ayush Karmacharya, Timothy Sue, Judy Fox<br>
**Análise de sentimento na precificação de ativos na bolsa brasileira** - https://dspace.mackenzie.br/items/8a782e25-1ec6-4367-82a2-0dba91fbc3f7 - Felipe da Silva Morishita Garbi, Matheus Barbosa Ferrari (Projeto de TCC)<br>
**Smarter, smaller, safer: The case for small language models in financial services** - https://www.infosys.com/iki/perspectives/small-language-models-financial-services.html - Vaibhav Bhokare, Amit Kumar Gupta e Sharan Bathija<br>
**Harnessing the power of small language models in financial services** - https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/events/approved/reinvent-2025/reinvent/2024/slides/fsi/FSI309_Harnessing-the-power-of-small-language-models-in-financial-services.pdf - Vikram Elango e Shreyas Subramanian<br>
**UV Labs vs BloombergGPT vs FinGPT vs Scale AI** - https://uvlabs.ai/blog/uv-labs-vs-alternatives <br>
**Automated Client Segmentation and Personalized Financial Guidance: Ethical Considerations in AI-Augmented Advisory Services** - https://wjaets.com/sites/default/files/fulltext_pdf/WJAETS-2026-0066.pdf - Souratn Jain<br>

## Prompt
Aqui serão apresentados alguns exemplos básicos de prompt junto de suas respostas. Outros serão apresentados em outro arquivo.

### Exemplo 1
Prompt: Explique brevemente como algoritmos de machine learning são utilizados em mercado financeiro.

Output: Os algoritmos de **machine learning (ML)** são amplamente aplicados no mercado financeiro para transformar grandes volumes de dados numéricos e textuais em previsões e decisões automatizadas de investimento. As principais formas de utilização incluem:

* **Previsão de Preços, Retornos e Volatilidade**: Modelos como redes neurais (redes *feedforward*, CNNs, LSTMs), árvores de decisão (*Random Forests*, *Gradient Boosting*) e modelos lineares regularizados (LASSO, Ridge) são empregados para capturar relações não lineares e complexas em séries temporais financeiras, prevendo a direção e o retorno de ações, títulos e índices.
* **Análise de Sentimento e Processamento de Linguagem Natural (NLP / LLMs)**: Modelos de linguagem (como FinBERT e Grandes Modelos de Linguagem - LLMs) analisam fontes não estruturadas de informação — notícias financeiras, relatórios corporativos (10-K), mídias sociais e transcrições de chamadas de resultados — para quantificar a percepção do mercado e gerar sinais de negociação (*trading signals*).
* **Trading Algorítmico e Microestrutura de Mercado**: Sistemas automatizados utilizam aprendizado de máquina para examinar a dinâmica do livro de ofertas (*limit order book*), identificando padrões de microestrutura para otimizar a execução de ordens de alta frequência e minimizar custos de transação e seleção adversa.
* **Sistemas de Negociação Multiagente**: Estruturas recentes baseadas em LLMs simulam a dinâmica de empresas de negociação através de múltiplos agentes autônomos com papéis especializados (analistas fundamentais, técnicos, de sentimento e gerentes de risco) que colaboram para tomar decisões de compra e venda.
* **Gestão de Portfólio e Aprendizado por Reforço**: Algoritmos de **Reinforcement Learning (RL)** e modelos de pesos parametrizados otimizam dinamicamente a alocação de ativos em carteiras, buscando maximizar o retorno ajustado ao risco (como o Índice de Sharpe) e adaptando-se às mudanças contínuas do mercado.
* **Gestão de Risco e Estabilidade Financeira**: Modelos de classificação e *ensembles* funcionam como sistemas de alerta precoce (*Early Warning Models*) para prever eventos de crédito, inadimplência corporativa, falências e vulnerabilidades sistêmicas no setor bancário.
* **Simulação de Mercado e Geração de Dados Sintéticos**: Redes gerativas (*Market Generators*, como GANs) criam cenários sintéticos de preços e volatilidade que preservam as propriedades estatísticas do mercado real, sendo fundamentais para testes de estresse, simulação de riscos e treinamento de modelos estratégicos (*backtesting*).

💡 *Se quiser aprofundar em algum desses pontos, podemos explorar como os modelos de linguagem (LLMs) são aplicados especificamente na análise de sentimento ou estruturar uma comparação entre modelos tradicionais e aprendizado profundo no mercado financeiro.*

### Exemplo 2
Prompt: Cite os principais algoritmos utilizados em mercado financeiro. Também cite, dentro das fontes, onde estudar cada um deles

Output: Com base nos materiais da sua biblioteca, os principais algoritmos de **machine learning** e **inteligência artificial** utilizados no mercado financeiro dividem-se em seis grandes famílias. Abaixo estão especificados quais são esses algoritmos e exatamente em quais fontes e capítulos estudá-los:

---

#### 1. Modelos Lineares e Regularizados (LASSO, Ridge, Elastic Net, Regressão Logística)
* **O que fazem**: Selecionam variáveis preditivas, reduzem o ruído em grandes conjuntos de dados e realizam previsões de retornos de ativos, probabilidade de inadimplência e crises financeiras.
* **Onde estudar nas suas fontes**:
  * **[M. F. Dixon et al.]**: O **Capítulo 1** e o **Capítulo 3** detalham a formulação matemática da regressão linear, regularização frequentista e regressão Bayesiana.
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: O **Capítulo 11** ("The ML Pipeline") cobre a implementação prática de Ridge, LASSO, Elastic Net e Regressão Logística.
  * **[Christian Bayer et al.]**: A **Seção 4** explica modelos de regularização (LASSO e Ridge) e sua aplicação no alerta precoce de crises financeiras.
  * **[B. Kelly & D. Xiu]**: A **Seção 3** faz análises comparativas de modelos penalizados para previsão de retornos em painéis de ações.

---

#### 2. Algoritmos Baseados em Árvores e Ensembles (Random Forests, Gradient Boosting - XGBoost, LightGBM, CatBoost)
* **O que fazem**: Capturam relações não lineares e interações complexas entre múltiplos fatores de mercado, sendo amplamente aplicados em risco de crédito, previsão de volatilidade e seleção de ações.
* **Onde estudar nas suas fontes**:
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: O **Capítulo 12** ("Gradient Boosting and Advanced Tabular Models") detalha o uso de XGBoost, LightGBM, CatBoost e interpretação via TreeSHAP.
  * **[Consoli&Recupero&Saisana]**: A **Seção 3** dedica-se ao funcionamento dos *ensembles* de árvores de decisão (Bagging, Random Forests, Boosting).
  * **[B. Kelly & D. Xiu]**: A **Seção 3.8** compara o desempenho prático de Random Forests (RF) e Gradient Boosted Regression Trees (GBRT) na construção de portfólios *long-short*.

---

#### 3. Redes Neurais Profundas e Sequenciais (RNN, LSTM, GRU, CNN, Autoencoders)
* **O que fazem**: As **RNNs, LSTMs e GRUs** modelam dependências temporais e não lineares em séries históricas de preços e no livro de ofertas (*limit order book*). As **CNNs** identificam padrões em gráficos de preços e matrizes de dados, enquanto **Autoencoders** comprimem centenas de características em fatores estatísticos de risco.
* **Onde estudar nas suas fontes**:
  * **[M. F. Dixon et al.]**: 
    * **Capítulo 4**: Conceitos fundamentais de redes neurais *feedforward*.
    * **Capítulo 8**: Redes neurais recorrentes (RNNs, LSTMs, GRUs), CNNs para dados temporais e Autoencoders para compressão de fatores e redução de dimensionalidade.
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: O **Capítulo 13** foca em arquiteturas profundas para séries temporais (LSTM, PatchTST, TCN, Mamba) e o **Capítulo 14** aborda Autoencoders condicionais e modelos de fatores latentes.
  * **[B. Kelly & D. Xiu]**: A **Seção 3.7** analisa Redes Neurais Vanilla e a **Seção 5.5** demonstra o uso de LSTMs na estimação do Fator de Desconto Estocástico (SDF).

---

#### 4. Aprendizado por Reforço (Reinforcement Learning - Q-Learning, DQN, PPO, G-Learning, Inverse RL)
* **O que fazem**: Otimizam sequências de decisões dinâmicas em ambientes com custos de transação, impacto de mercado e restrições de liquidez, sendo aplicados na execução ótima de ordens, *market making* e precificação/hedge de derivativos.
* **Onde estudar nas suas fontes**:
  * **[M. F. Dixon et al.]**:
    * **Capítulo 9**: Fundamentos de Processos de Decisão de Markov (MDP) e Q-Learning.
    * **Capítulo 10**: Aplicações práticas, incluindo o modelo QLBS para precificação de opções e G-Learning para gestão de carteiras de ações.
    * **Capítulo 11**: Aprendizado por Reforço Inverso (IRL) e Aprendizado por Imitação para inferir funções de recompensa a partir do comportamento de mercado.
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: O **Capítulo 21** detalha algoritmos de RL (DQN, PPO, SAC) aplicados à execução ótima de ordens, *market making* e *deep hedging*.

---

#### 5. Modelos de Linguagem e Sistemas de Agentes AI (FinBERT, LLMs, Agentes Multiagente, RAG)
* **O que fazem**: Processam textos não estruturados (notícias, relatórios 10-K, chamadas de resultados) para quantificar o sentimento, mapear redes de empresas e simular mesas de negociação automatizadas com agentes especializados.
* **Onde estudar nas suas fontes**:
  * **`The New Quant: A Survey of Large Language Models in Financial Prediction and Trading`**: Estudo sobre o ciclo de vida do uso de LLMs (FinBERT, BloombergGPT, LLaMA), conectando RAG, análise de sentimento e sistemas multiagente à construção de portfólios.
  * **`TradingAgents: Multi-Agents LLM Financial Trading Framework`**: Detalha a arquitetura de um ecossistema multiagente com papéis especializados (analistas fundamentais, técnicos, de sentimento e gerentes de risco).
  * **`A Review of Large Language Models for Stock Price Forecasting from a Hedge-Fund Perspective`**: Explora o uso de LLMs para análise de relatórios anuais (10-K), conferências de resultados e tokenização de séries temporais de preços.
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: Os **Capítulos 10, 22 e 24** abordam processamento de texto com FinBERT, RAG fundamentado em documentos da SEC e agentes autônomos.

---

#### 6. Geradores de Mercado e Dados Sintéticos (GANs, TimeGAN, VOLGAN, SDEs Neurais)
* **O que fazem**: Criam trajetórias de preços e superfícies de volatilidade sintéticas que preservam as propriedades estatísticas reais, permitindo treinar modelos e realizar testes de estresse em cenários de mercado raros.
* **Onde estudar nas suas fontes**:
  * **[Christian Bayer et al.]**: Apresenta a utilização de *Market Generators* (como VOLGAN, Fin-GAN e SDEs Neurais Condicionais) para simular pares de moedas e superfícies de volatilidade sem arbitragem.
  * **`GitHub - stefan-jansen/machine-learning-for-trading`**: A visão geral da obra e o **Capítulo 21** destacam geradores sintéticos como TimeGAN, Tail-GAN e modelos de difusão para validação de estratégias.

---

💡 *Se quiser iniciar os estudos por uma abordagem mais prática em código, podemos montar um roteiro de leitura baseado nos repositórios e livros focados em Python.*


## Conclusão
O uso do NotebookLm (também Gemini Notebook) é uma maneira simples de estruturar um chatbot de IA utilizando fontes fornecidas. O fato de utilizarmos fontes que nós mesmo fornecemos e podermos solicitar onde exatamente o modelo encontrou essa referência dentro das fontes diminui muito a chance de alucinação. Além disso, o uso dessa ferramenta tem a capacidade de ajudar a organizar os estudos em um novo tópico. Um pipeline interessante para estudar um novo tópico é:
1) Utilizar IA para angariar fontes tradicionais/bem estabelecidas no tópico
2) Utilizar o Notebook para centralizar todas as fontes
3) Realizar perguntas, solicitar a criação de resumos, e até montar um guia de estudos

Os demais arquivos presentes nesse repositório conterão uma maior exploração das fontes utilizando o NotebookLM.
