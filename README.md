## End to End Machine Learning Project

1. Set up the github (repository)

   a) new enviroment
   
   b) setup.py
   
   c) requirements.txt

Descrição:
a)
  - Criar um repositório na conta online do github (sem nada)
  - criar uma pasta local no computador (sem nada)
  - Abrir o VScode pelo terminal conda com o comando code . 
  - Abrir o terminar no VScode e trocar para prompt windows
  - Criar um ambiente virtual com o comando: conda create -p venv python==3.8 -y
  - Ativar o ambiente virtual com o comando: conda activate venv/
  - Sincronizar repositório git local com o online seguindo os passos do github
  - Criar arquivo README.md
  - Criar arquivo .gitignore no github

b e c)
  - Criar o arquivo requirements.txt (no VScode) com os nomes e versões das bibliotecas necessárias
  - Criar o arquivo setup.py (copiar código) no VScode

2. Src folder and build the package

  - Criar pasta src no VScode
  - Criar arquivo "__init__.py" dentro da pasta src (no VScode)
  - rodar o comando: pip install -r requirements.txt no terminal
  - Verificar se foi criado o pacote ml_project.egg-info

3. Create project structure

   - Criar pasta components contendo (arquivos em branco):
      - init.py
      - data_ingestion.py
      - data_transformation.py
      - model_trainer.py
   - Criar pasta pipele contendo:
      - init.py
      - predict_pipeline.py
      - train_pipeline.py
   - Project logging module implementation
   - Testing Logging and Exception Handling

4. Create 'notebook' folder with a 'data' folder and the notebooks needed to the project

5. Write data_ingestion.py file and run file 
   - This file already creates train and test artifacts
   - don't forget to add ".artifacts" in .gitignore

6. Preencher arquivo data_transformation.py
   - classe transformation conig
   - criar função 'save_obj' no arquivo utils
   - chamar funções da data_transformation no data_ingestion.py