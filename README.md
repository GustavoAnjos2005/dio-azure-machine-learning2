## 🧠 Sobre o Projeto

A ideia central é utilizar NLP para interpretar perguntas e encontrar respostas relevantes em textos extraídos de PDFs. Para isso, aplicamos técnicas como:

- Extração e pré-processamento de texto
- Análise semântica e compreensão de linguagem natural
- Busca por similaridade entre perguntas e sentenças
- (Opcional) Modelos pré-treinados para responder perguntas

Apesar de este repositório conter apenas as sentenças, todo o raciocínio foi baseado na construção de uma solução completa, envolvendo:

- Processamento de arquivos PDF
- Criação de embeddings das sentenças
- Comparação de similaridade com perguntas feitas pelo usuário
- Retorno da resposta mais provável

## ✍️ Sentenças analisadas

As sentenças estão disponíveis no arquivo `inputs/sentencas.txt`. Elas foram utilizadas como base para as análises feitas pelo chatbot.

Exemplo de algumas sentenças:

- "O Machine Learning é uma subárea da Inteligência Artificial."
- "Chatbots podem ser treinados para responder perguntas específicas."
- "Processamento de Linguagem Natural é fundamental para entender o conteúdo de textos."
- "PDFs podem conter informações valiosas para empresas."
- "Modelos de IA podem ser utilizados para automatizar processos repetitivos."

## 💡 Insights e Aprendizados

Durante a criação do projeto, alguns pontos se destacaram:

- A importância do pré-processamento de texto para obter resultados mais precisos
- A relevância de ferramentas modernas de NLP para tarefas como essa (como spaCy, Transformers, etc.)
- A possibilidade de escalar esse tipo de solução com APIs e serviços em nuvem
- Como perguntas mal formuladas podem influenciar diretamente na qualidade das respostas
- ![chatdio](https://github.com/user-attachments/assets/5ef5c5d0-5f6f-4a39-af4d-4a38750e86bd)


## 🚀 Possibilidades futuras

- Permitir upload de PDFs diretamente pelo usuário
- Criar uma interface web com Streamlit ou Flask
- Integrar com APIs de chatbot como Telegram ou WhatsApp
- Utilizar embeddings vetoriais e ferramentas como FAISS para busca semântica

---
