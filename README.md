<h1> 🧠 Aprendizado Supervisionado no Neurônio Perceptron </h1>

- Projeto prático da disciplina Redes Neurais Artificiais 2025.1, com o objetivo de implementar o algoritmo de treinamento mediante Aprendizado Supervisionado do neurônio Perceptron de Rosenblatt, aplicado em problemas de classificação.


<h3>Integrantes da Equipe</h3>

|Aluno|Matrícula|
|-|-|
|Adriana Raffaella|2315080067|
|Ana Flavia|2315080055|
|Guilherme Moraes|2315080008|
|Yago Feitoza|2115080027|

<br/>

 <h2>📁 Estrutura do Projeto</h2>

 ```
 ├── NeuronioPerceptron.ipynb    # Notebook do Projeto
└── README.md                   # README explicando o projeto
 ```

<br/>

<h2>📊 Datasets usados</h2>

1. `dataAll.txt`

2. `data3.txt`

3. `dataHoldout.txt`

<br/>

<h2>⚙️ Tecnologias Utilizadas</h2>
<table>
  <tr>
    <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40px;" alt="Logo do Python"/><br />
        <sub><b>Python</b></sub>
    </td>
    <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="40px;" alt="Logo do NumPy"/><br />
        <sub><b>NumPy</b></sub>
    </td>
    <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" width="40px;" alt="Logo do Matplotlib"/><br />
        <sub><b>Matplotlib</b></sub>
    </td>
    <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="40px;" alt="Logo do pandas"/><br />
        <sub><b>pandas</b></sub>
    </td>
    <td align="center">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="40px;" alt="Logo do scikit-learn"/><br />
        <sub><b>scikit-learn</b></sub>
    </td>
  </tr>
</table>

<br/>

<h2>🧪 Etapas do Projeto</h2>

<h3>Parte I – Resolvendo um Problema Linearmente Separável</h3>

- Nessa etapa, foi construído o neurônio Perceptron e seu algoritmo de treinamento (o método `train`) com o fito de resolver o problema de classificação proposto, usando o dataset `dataAll.txt`;

<h3>Parte II – Experimentação</h3>

- Usando o dataset da equipe (`data3.txt`) e o Perceptron desenvolvido, realizaram-se diferentes experimentos de aprendizado, dos quais se extraíram a média e o desvio padrão da quantidade de ajustes efetuados no vetor de pesos e o menor número de épocas até a convergência nestas iterações;

- Os resultados foram exibidos com o auxílio da biblioteca `prettytable`;

<h3>Parte III – Validação Holdout em Problema Não-Linearmente Separável</h3>

- Usamos o algoritmo do Perceptron e a validação holdout para separar as classes do dataset `dataHoldout.txt`, e evidenciamos por meio de gráficos que se trata de um problema não-linearmente separável. 

<br/>

<h2>🧠 Resultados</h2>

|Métricas|Valor|
|-|-|
|Acurácia|0.9583|
|Precisão|0.9032|
|Revocação|0.9333|
|F1-score|0.9180|

<br/>

<h2>📌 Observações</h2>

<h3>Limitações do Perceptron</h3>

- Apesar dos bons resultados, o modelo cometeu alguns erros de classificação;

<h3>Possíveis melhorias futuras</h3>

- Recomenda-se avaliar o modelo com **validação cruzada**;

- Comparar o modelo com classificadores não lineares;

- Verificar a performance com diferentes taxas de aprendizado e épocas de treinamento.

<br/>

<h2>🧑‍💻 Equipe</h2>
<table>
  <tr>
    <td align="center">
    <a href="https://github.com/RaffaellaSantos">
        <img src="https://avatars.githubusercontent.com/RaffaellaSantos" width="100px;" alt="Foto da Adriana Raffaella"/><br />
        <sub><b>Adriana Raffaella</b></sub>
        </a>
    </td>
    <td align="center">
    <a href="https://github.com/flavia-segadilha">
        <img src="https://avatars.githubusercontent.com/flavia-segadilha" width="100px;" alt="Foto da Ana Flavia"/><br />
        <sub><b>Ana Flavia</b></sub>
        </a>
    </td>
    <td align="center">
    <a href="https://github.com/guighm">
        <img src="https://avatars.githubusercontent.com/guighm" width="100px;" alt="Foto do Guilherme Moraes"/><br />
        <sub><b>Guilherme Moraes</b></sub>
        </a>
    </td>
    <td align="center">
    <a href="https://github.com/yagofeitoza19">
        <img src="https://avatars.githubusercontent.com/yagofeitoza19" width="100px;" alt="Foto do Yago Feitoza"/><br />
        <sub><b>Yago Feitoza</b></sub>
        </a>
    </td>
  </tr>
</table>