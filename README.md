📚 Chatbot Inteligente Baseado em PDFs - Foco em Transtorno de Ansiedade Generalizada (TAG)
Este projeto foi desenvolvido como parte do desafio da DIO para aplicar conceitos de IA generativa, embeddings e buscas vetorizadas em um chatbot interativo que responde com base em conteúdos extraídos de arquivos PDF.

🎯 Objetivo
Criar um sistema de busca inteligente que:

📥 Carrega arquivos PDF relevantes sobre o tema Transtorno de Ansiedade Generalizada (TAG);

📚 Indexa os conteúdos utilizando técnicas de embeddings e busca vetorial;

💬 Permite ao usuário fazer perguntas e obter respostas contextualizadas com base nos documentos;

🤖 Utiliza IA para gerar respostas fundamentadas e úteis para estudos e pesquisas.

🧠 Contexto
Como estudante de Psicologia, precisei revisar diversos artigos científicos para meu TCC. Diante da dificuldade de correlacionar as informações entre múltiplos textos, optei por desenvolver esse sistema de assistência virtual com IA para organizar e extrair os dados de forma eficiente.

🛠️ Tecnologias Utilizadas
Python

LangChain

FAISS (ou outro indexador vetorial como ChromaDB)

OpenAI API (ou alternativa de modelo local)

Streamlit (para o front-end do chat)

PyMuPDF ou pdfplumber (para leitura dos PDFs)

🗂️ Estrutura do Projeto
bash
Copy
Edit
📁 inputs/
└── exemplo.txt  # Sentenças de exemplo utilizadas nos testes iniciais

📁 src/
└── main.py      # Lógica principal do carregamento, indexação e interação com o usuário

README.md        # Este arquivo
🧪 Como Funciona
O usuário faz upload de um ou mais PDFs.

O conteúdo é processado e transformado em vetores semânticos.

As perguntas são convertidas em vetores e comparadas com os documentos.

As respostas são geradas com base nos trechos mais relevantes.

📸 Prints do Projeto
![image](https://github.com/user-attachments/assets/35da29d1-e7da-4709-a01c-db275c97cd8e)
![image](https://github.com/user-attachments/assets/2aabba47-ffcf-4e1e-b253-7c9dccff04da)


💡 Insights e Possibilidades
Facilidade para revisar dezenas de documentos em poucos minutos;

Rápida localização de trechos-chave sobre o TAG;

Possibilidade de expandir o projeto para outras áreas de conhecimento;

Uso em contextos clínicos, educacionais ou corporativos com diferentes bases de dados.

🚀 Como Rodar o Projeto
Clone este repositório:

bash
Copy
Edit
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
Instale as dependências:

bash
Copy
Edit
pip install -r requirements.txt
Execute o chatbot:

bash
Copy
Edit
streamlit run src/main.py
📬 Entrega do Projeto
Este repositório foi submetido como parte do desafio da DIO. Agradeço pela oportunidade de aplicar os conceitos aprendidos e explorar novas formas de usar a inteligência artificial de maneira prática e relevante.
