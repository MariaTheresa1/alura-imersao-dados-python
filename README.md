# Imersão de Dados com Python Alura
O projeto é dashboard interativo criado durante um curso de Imersão de Dados com Python disponibilizado pela Alura. O dashboard utiliza bibliotecas como streamlit, pandas e o módulo express da biblioteca plotly usa como base dados salariais dos últimos anos de profissionais que atuam na área de dados.

Link do deploy do app na streamlit https://mariatheresa1-alura-imersao-dados-python-app-jrmjen.streamlit.app/

<img width="1916" height="852" alt="dashboard-analise-dados" src="https://github.com/user-attachments/assets/a005d22f-119a-4577-ac2e-d7a18da3bc17" />

1. Para rodar na sua máquina local: 
- Requisitos: python instalado na sua máquina. 
- Criar o ambiente virtual:
`py -m venv .venv`
- Ativar o ambiente virtual em Windows:
`.\.venv\Scripts\Activate`
(Caso dê problema "O arquivo não pode ser carregado", comando para liberar a execução de scripts no PowerShell: `Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass`)
- Instalar as bibliotecas necessárias
`pip install -r requirements.txt`
- Comando para executar o app: 
`streamlit run app.py`, geralmente disponível em http://localhost:8501

2. Para fazer o deploy, basta criar uma conta no streamlit, vincular com sua conta no github e subir o projeto.

Link do projeto no colab referentes às outras atividades do curso usando a mesma base de dados: [Projeto Colab Imersão de Dados com Python Alura](https://colab.research.google.com/drive/1ZjwGAIjIT12sJtukYOROtNnFDCAouZ1j)
