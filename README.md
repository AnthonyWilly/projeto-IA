# RAG Study Agent — Avaliação Comparativa com RAGAS

Projeto acadêmico da disciplina de Inteligência Artificial (UFCG).  
Construção de um agente RAG sobre o livro-texto da disciplina, fine-tuning 
de LLM e avaliação comparativa entre três modelos.

## Visão Geral

| Notebook | Descrição |
|---|---|
| `Agente_de_estudo_de_IA.ipynb` | Pipeline RAG com LangChain, embeddings Gemma 300M e ChromaDB |
| `IA_QAT_Gemma3_4B.ipynb` | Fine-tuning do Gemma 3 4B com LoRA via Unsloth no dataset RAFT (adaptado do pipeline oficial Unsloth)|
| `avaliacao_rag.ipynb` | Avaliação comparativa dos 3 cenários com métricas RAGAS |

## Modelos Avaliados

- GPT-OSS 120B
- Gemma 3 4B Base
- Gemma 3 4B Fine-tuned (LoRA/Unsloth, dataset RAFT)

## Métricas (RAGAS)

- Faithfulness
- Answer Correctness
- Context Precision
- Context Recall

## Stack

LangChain · HuggingFace · ChromaDB · Unsloth · RAGAS · Ollama · Python
