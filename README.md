#ytb-lumen

Ferramenta em Python para transcrição e análise de podcasts/entrevistas no YouTube, com extração de metadados e geração de insights a partir do conteúdo falado.

Python-based software for transcribing and analyzing YouTube podcasts and interviews. Extracts metadata and generates insights from spoken content.

#Video Analyzer

Este projeto tem como objetivo analisar vídeos (principalmente entrevistas e podcasts), transcrevê-los e extrair os principais insights. O foco inicial é em vídeos MP4, com transcrição para rascunho e identificação precisa de perguntas e respostas, além da extração de ideias principais e tópicos por pergunta. A interface será uma GUI simples e os relatórios serão em texto.

## Estrutura do Projeto

```
video_analyzer/
├── data/                 #Para armazenar vídeos de entrada e outros dados
├── src/                  
│   ├── __init__.py
│   ├── transcription.py  #Módulo para transcrição de áudio/vídeo
│   ├── nlp_analysis.py   #Módulo para análise de NLP e extração de insights
│   └── gui.py            #Módulo para a interface gráfica
├── requirements.txt      #Dependências do projeto
├── .gitignore            
└── README.md             #Este arquivo
```

## Instalação

1. Clone o repositório:
  
2. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```








