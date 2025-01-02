# Assistente Financeiro Baseado em IA

Este projeto utiliza a biblioteca LangChain para criar um assistente financeiro pessoal, capaz de responder perguntas relacionadas a finanças e investimentos. A aplicação integra ferramentas para realizar cálculos financeiros, buscar informações atualizadas na internet e fornecer respostas em português brasileiro.

## 🚀 Funcionalidades

1. **Respostas personalizadas**: O assistente utiliza um modelo de linguagem avançado (GPT-3.5-Turbo).
2. **Execução de cálculos**: Com a ferramenta Python REPL, o assistente realiza cálculos financeiros diretamente.
3. **Busca de informações**: A integração com o DuckDuckGo permite ao assistente trazer dicas de economia e investimentos atualizadas.

## 🛠️ Tecnologias Utilizadas

- **LangChain**: Framework para integração de agentes e ferramentas.
- **OpenAI GPT-3.5-Turbo**: Modelo de linguagem para respostas naturais e contextualizadas.
- **DuckDuckGoSearchRun**: Ferramenta para realizar buscas na internet.
- **Python REPL**: Shell Python integrado para cálculos e análises dinâmicas.

## 📁 Estrutura do Código

1. **Configuração do Modelo**: Inicialização do modelo de linguagem com `ChatOpenAI`.
2. **Templates de Prompt**: Personalização do comportamento do assistente com prompts.
3. **Ferramentas Integradas**:
   - Python REPL para cálculos.
   - DuckDuckGoSearchRun para buscas online.
4. **Agente React**: Criação e execução do agente com instruções pré-definidas.
5. **Execução de Perguntas**: Exemplo de uso com uma questão financeira simulada.

## 📜 Como Executar o Projeto

1. **Instale as dependências**:
   Certifique-se de ter Python instalado. Use `pip` para instalar as bibliotecas:

   ```pip install langchain langchain-community langchain-openai```

2. **Configure sua chave de API**:
   Em `os.environ["YOUR_API_KEY"]` no código coloque sua chave api para carregar o OpenAI api. `Certifique-se de que sua chave não seja compartilhada publicamente.`

3. **Execute o script**: Salve o código fornecido como `assistente_financeiro.py` e execute-o:
   ```python assistente_financeiro.py```

4. **Teste com perguntas**: Insira perguntas financeiras em `QUESTION` no código.

## **🔒 Considerações de Segurança**:
1. **Chaves de API**: Remova ou substitua sua chave API do código antes de compartilhar publicamente.
2. **Dados Sensíveis**: Não inclua informações confidenciais ou sensíveis no código ou exemplos.

## **📝 Exemplo de Pergunta**:
Minha renda é de R$10000 por mês, o total de minhas despesas é de R$8500 mais 1000 de aluguel.
Quero fazer uma renda extra.
Quais dicas de você me dá?

