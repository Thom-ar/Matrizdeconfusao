# Matrizdeconfusao
Este projeto visa construir uma matriz de confusão para avaliar o desempenho de um modelo de classificação em Python. O código está contido no arquivo Jupyter Notebook Construindo_uma_Matriz_de_Confusão_em_Python.ipynb.

Passos do Código
Importação de Bibliotecas: Importa bibliotecas essenciais como pandas, numpy, seaborn, matplotlib, e funções específicas do scikit-learn.
Carregamento de Dados: Carrega o dataset Employee.csv e exibe as primeiras linhas.
Tratamento de Dados: Converte variáveis categóricas em variáveis dummy para preparação do modelo.
Análise da Variável Target: Analisa a variável target LeaveOrNot, que indica se um funcionário vai sair ou não da empresa.
Criação do Modelo: Utiliza a regressão logística para criar um modelo de classificação.
Construção da Matriz de Confusão: Avalia o desempenho do modelo utilizando uma matriz de confusão.
Requisitos de Instalação
Para executar este projeto, você precisa ter Python instalado em seu sistema. Além disso, você deve instalar as bibliotecas necessárias.

Passos de Instalação
Clone o repositório

bash
git clone https://github.com/Thom-ar/Matrizdeconfusao.git
cd Matrizdeconfusao
Crie um ambiente virtual

bash
python -m venv venv
source venv/bin/activate   # No Windows, use `venv\Scripts\activate`
Instale as dependências

bash
pip install pandas numpy seaborn matplotlib scikit-learn
Execute o Jupyter Notebook

bash
jupyter notebook
Abra o arquivo Construindo_uma_Matriz_de_Confusão_em_Python.ipynb no Jupyter Notebook e execute as células para reproduzir o projeto.

Contribuição
Sinta-se à vontade para contribuir com este projeto. Você pode fazer um fork do repositório, criar um branch, adicionar suas modificações e abrir um pull request.
