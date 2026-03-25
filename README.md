# ⛓️ Miniguia de Estudos: Blockchain do Zero com NotebookLM

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)
![Tema](https://img.shields.io/badge/Tema-Blockchain-blue)
![Foco](https://img.shields.io/badge/Foco-Smart_Contracts-purple)
![Ferramenta](https://img.shields.io/badge/IA-NotebookLM-orange)

## 🎯 Contexto e Objetivos

**O que é este projeto:** Um repositório criado para um desafio de projeto focado em explorar o potencial do Google NotebookLM como assistente de estudos.

**Tema Central:** Blockchain, abordando desde os conceitos iniciais até a arquitetura de redes descentralizadas.

**Aprofundamento Prático:** Estudo detalhado sobre a aplicação e o funcionamento de Contratos Inteligentes (Smart Contracts), especialmente na rede Ethereum.

**Principais Metas de Estudo:**
* Desmistificar a tecnologia Blockchain, separando-a do conceito exclusivo de criptomoedas.
* Compreender a estrutura básica: blocos, hashes, nós e mecanismos de consenso.
* Entender como os Smart Contracts eliminam intermediários no mundo real.
* Praticar a engenharia de prompts estruturados para evitar alucinações da IA e gerar resumos confiáveis.

## 📚 Curadoria de Fontes

**Critério de Seleção:** Foram escolhidas 5 fontes de altíssima autoridade para alimentar o NotebookLM, garantindo respostas precisas e com embasamento técnico, mercadológico e acadêmico.

**Fontes Utilizadas no Caderno Temático:**
* **NIST - Blockchain Technology Overview (IR 8202):** Documentação oficial com rigor técnico sobre a arquitetura exata de redes blockchain.
* **IBM Developer - Blockchain 101:** Guia rápido focado na aplicação corporativa da tecnologia.
* **Microsoft - Beginners Series to Blockchain:** Conteúdo didático focado em conceitos introdutórios e amigáveis.
* **Binance Academy:** Explicações didáticas sobre o funcionamento prático do ecossistema cripto.
* **KriptoBR - Smart Contracts: Usos e Limitações no Mundo Real:** Artigo aprofundado sobre contratos inteligentes, rede Ethereum, casos de uso (como DeFi) e os desafios de implementação.

## 🛠️ Engenharia de Prompts e "Cicatrizes"

**Estratégia Adotada:** O processo de estudo exigiu o refinamento constante das perguntas. Abaixo estão documentados os testes, as falhas e os acertos (troubleshooting):

### Tentativa 1: O Prompt Genérico
* **Prompt Testado:** "Explique o que é blockchain com base nessas fontes."
* **Resultado Obtido:** Resposta excessivamente densa e focada em criptografia pesada (baseada no documento do NIST).
* **Cicatriz/Aprendizado:** Pedir explicações abertas sem definir uma "persona" gera respostas pouco didáticas para iniciantes.

### Tentativa 2: O Prompt Guiado por Analogia
* **Prompt Testado:** "Atue como um professor de tecnologia para iniciantes. Usando as fontes da Binance e da Microsoft, explique o que é blockchain em até 3 parágrafos. Use a analogia de um livro-razão (ledger) público."
* **Resultado Obtido:** Excelente nível de compreensão. A IA isolou a matemática complexa e focou no conceito de "livro de registros digital compartilhado".

### Tentativa 3: Aprofundamento em Smart Contracts e Casos de Uso
* **Prompt Testado:** "Como um professor de tecnologia para iniciantes. Explique-me os conceitos de criação de contratos inteligentes (smart contracts) em redes Ethereum e em que situações esses contratos são aplicados em até cinco parágrafos."
* **Resumo do Resultado Obtido:**
  * A IA utilizou a fonte da KriptoBR com perfeição.
  * Explicou os contratos como "máquinas de venda automática" (códigos autoexecutáveis).
  * Destacou o Ethereum como a plataforma principal para aplicativos descentralizados.
  * Apontou casos de uso fortes, como DeFi e DEX (corretoras descentralizadas).
  * Alertou criticamente para as limitações: riscos de programação e a necessidade de Oráculos para ler dados externos.

### Tentativa 4: Extração de Dados Específicos
* **Prompt Testado:** "De acordo APENAS com o documento do NIST (IR 8202), liste em bullet points os componentes fundamentais de uma arquitetura blockchain."
* **Resultado Obtido:** Precisão absoluta na listagem de componentes técnicos, sem misturar com os materiais de marketing das outras fontes.

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado: Blockchain e Smart Contracts

**A Base da Blockchain:**
* Funciona como um banco de dados distribuído (livro-razão) replicado entre vários computadores (nós).
* Garante descentralização (sem controle de um órgão único) e imutabilidade (dados selados criptograficamente não podem ser apagados ou alterados).

**A Revolução dos Contratos Inteligentes:**
* São linhas de código armazenadas na blockchain que se autoexecutam ao atingir regras pré-programadas.
* O principal benefício é a eliminação de intermediários de confiança (como bancos, corretoras ou cartórios).

**O Papel da Rede Ethereum:**
* Foi projetada não apenas para ser dinheiro digital (como o Bitcoin), mas para hospedar Smart Contracts e Aplicativos Descentralizados (dApps), usando linguagens próprias como o Solidity.

**Aplicações Reais e Desafios:**
* **Caso de Sucesso:** O setor de DeFi (Finanças Descentralizadas), que viabiliza empréstimos e trocas sem instituições financeiras centrais.
* **Limitações Atuais:** Falhas de código podem gerar perdas financeiras irreversíveis. Além disso, a rede é "cega" ao mundo exterior, precisando de Oráculos (sistemas externos) para acessar dados do mundo real.

### 2. Glossário de Conceitos Principais
* **Nó (Node):** Computador conectado à rede que mantém uma cópia do livro-razão e valida novas transações.
* **Hash Criptográfico:** Impressão digital única que garante que os dados de um bloco não sofreram adulteração.
* **Smart Contracts:** Programas autoexecutáveis baseados em regras lógicas do tipo "se X acontecer, execute Y".
* **Ethereum:** Principal rede blockchain focada na execução de contratos inteligentes.
* **dApps:** Aplicativos Descentralizados que rodam sobre a infraestrutura da blockchain, e não em servidores centrais.
* **DeFi (Finanças Descentralizadas):** Ecossistema de serviços financeiros operado inteiramente por códigos e contratos inteligentes.
* **Oráculos (Oracles):** Pontes tecnológicas que enviam dados do mundo real (ex: cotação do dólar, resultado de uma eleição) para dentro da blockchain.

### 3. Prompts Reutilizáveis para Revisão
* **Para testar conceitos técnicos:** "Gere 5 perguntas de múltipla escolha baseadas nas definições do documento do NIST para testar meu conhecimento sobre hashes e blocos."
* **Para comparar aplicações:** "Resuma as diferenças entre o uso de blockchain para criptomoedas (Binance) e a aplicação de contratos inteligentes no Ethereum (KriptoBR)."
* **Para aprofundamento específico:** "Explique o que são Finanças Descentralizadas (DeFi) e Oráculos, e como eles se relacionam, criando um FAQ com 3 perguntas e respostas rápidas."

## 🧑‍💼 Contato

[Linkedin](https://www.linkedin.com/in/anderson-ribeiro-carvalho)