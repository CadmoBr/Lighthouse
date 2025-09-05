# 📘 Projeto de Regressão IMDb

## 📌 Descrição
Este projeto realiza análise de dados de filmes (IMDb) e utiliza um modelo de regressão treinado (`modelo_regressao_imdb.pkl`) para prever variáveis de interesse. 
O notebook `Desafio_LightHouse.ipynb` contém o passo a passo da análise exploratória, treinamento e avaliação do modelo.

---

## ⚙️ Requisitos

Antes de executar, certifique-se de ter instalado:

- **Python 3.8+**
- **Bibliotecas** listadas no arquivo `requirements.txt`

Instale tudo com:

```bash
pip install -r requirements.txt
```

---

## 📂 Estrutura do Projeto

```
├── Desafio_LightHouse.ipynb     # Notebook principal do projeto
├── modelo_regressao_imdb.pkl    # Modelo treinado salvo
├── requirements.txt             # Dependências do projeto
├── README.md                    # Documentação do projeto
```

---

## ▶️ Como Executar

1. **Clone ou baixe o projeto**
   ```bash
   git clone <repositorio>
   cd <pasta-do-projeto>
   ```

2. **Crie um ambiente virtual (opcional, mas recomendado)**
   ```bash
   python -m venv venv
   source venv/bin/activate   # Linux/Mac
   venv\Scripts\activate    # Windows
   ```

3. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Abra o Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Depois, abra o arquivo `Desafio_LightHouse.ipynb`.

5. **Executando o modelo salvo**
   Dentro do notebook, você pode carregar o modelo da seguinte forma:

   ```python
   import joblib

   # Carregar modelo salvo
   modelo = joblib.load("modelo_regressao_imdb.pkl")

   # Exemplo de uso (substitua X_novo pelas features corretas)
   previsao = modelo.predict([X_novo])
   print(previsao)
   ```

---

## 📊 Resultados
- Análises gráficas no notebook (`matplotlib` / `seaborn`).
- Modelo de regressão salvo para previsões futuras.

---

## 👨‍💻 Autor
Projeto desenvolvido para o **Desafio LightHouse**.
