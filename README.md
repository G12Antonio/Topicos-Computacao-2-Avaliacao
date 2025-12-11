# Topicos-Computacao-2-Avaliacao
Este repositório contém os arquivos necessários para a entrega das atividades [Atividade Avaliativa 4 (AV2) - Estudo e Implementação sobre LLMs e RAGs] e [Atividade Avaliativa 3 (AV2) - Estudo e Implementação sobre Mecanismos de Atenção e Redes Transformers]. Os arquivos são os códigos que foram apresentados ao professor durante a aula no dia 10/12/2025 e os relatórios que descrevem as etapas, desenvolvimento e os resultados apresentados pelos códigos.

Disciplina:
TÓPICOS ESPECIAIS EM ENGENHARIA DE COMPUTAÇÃO

Turma:
EC10MA

Integrantes:
CAUÊ MARTINS
GABRIEL ANTONIO
GABRIEL GALEGO
JOÃO VITOR FARIAS
MURILO GUIMARÃES
WALLACE RICARDO

Atividades:
ATIVIDADE AVALIATIVA 3 (AV2) - ESTUDO E IMPLEMENTAÇÃO SOBRE MECANISMOS DE ATENÇÃO E REDES TRANSFORMERS
ATIVIDADE AVALIATIVA 4 (AV2) - ESTUDO E IMPLEMENTAÇÃO SOBRE LLMS E RAGS

Atividade Avaliativa 3 (AV2) - Estudo e Implementação sobre Mecanismos de Atenção e Redes Transformers:
Nesta atividade, foi apresentado o código sobre como funciona os mecanismos de atenção e redes transformers. O código usa 5 baselines (Majority class, TF + IDF LogReg (SGD), TF + IDF Multinomial NB, TF + IDF Linear SVM e BiLSTM), 4 modelos de transformers [RoBERTa - base (modelo padrão), RoBERTa + LoRA (PEFT) (modelo variante), RoBERTa + Ablações (duas configurações de ablações diferentes)]. O objetivo era treinar as redes transformers usando o dataset do rotten tomatoes para verificar se as mesmas conseguaim acertas as classificações positivas/negativas dispostas no dataset.
Arquivos: arquivo_transformers_rotten_tomatoes.ipynb; Relatório Técnico - Aplicação de Transformer.pdf

Atividade Avaliativa 4 (AV2) - Estudo e Implementação sobre LLMs e RAGs:
Nesta atividade, foi apresentado o código sobre como funciona os mecanismos de large language models (LLMs) e Retrieval-Augmented Generation (RAGs). O código usa 5 baselines (baseline padrão, RAG 1 – vector, chunk médio, top-k=5, RAG 2 – vector, chunk menor, top-k=8, RAG 3 – híbrido BM25 + vector + rerank e RAG 4 – LLM side melhorado (prompt estruturado + few-shot) + híbrido + rerank) e segue com os critérios: LangChain + Vector Store (Chroma), loader PDF, RecursiveCharacterTextSplitter, métricas Faithfulness e Context Precision, tabela/gráfico acerto/erro, demo Gradio. . O objetivo era criar um pequeno assistente virtual, que utiliza documentos nacionais como referência, para guiar usuários sobre perguntas relacionadas à dengue, como alerta, sintomas, medidas, prevenções e outros.
Arquivos: arquivo_llm_rag_dengue.ipynb; Relatório Técnico - Aplicação de LLM + RAG.pdf
