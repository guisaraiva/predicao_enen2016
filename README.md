# Desafio Codenation - Predição da Nota de Matemática - Enem 2016


O contexto do desafio gira em torno dos resultados do ENEM 2016 (disponíveis no arquivo train.csv). Este arquivo, e apenas ele, deve ser utilizado para todos os desafios. Qualquer dúvida a respeito das colunas, consulte o Dicionário dos Microdados do Enem 2016.

Muitas universidades brasileiras utilizam o ENEM para selecionar seus futuros alunos e alunas. Isto é feito com uma média ponderada das notas das provas de matemática, ciências da natureza, linguagens e códigos, ciências humanas e redação, com os pesos abaixo:

matemática: 3 
ciências da natureza: 2
linguagens e códigos: 1.5
ciências humanas: 1
redação: 3

No arquivo test.csv crie um modelo para prever nota da prova de matemática (coluna NU_NOTA_MT) de quem participou do ENEM 2016.
Salve sua resposta em um arquivo chamado answer.csv com duas colunas: NU_INSCRICAO e NU_NOTA_MT.

[Referência - Codenation](https://www.codenation.dev/aceleradev/ds-belohorizonte-1/)

# Importando as bibliotecas no jupyter notebook

![image](https://user-images.githubusercontent.com/15157510/66669261-76a94900-ec2d-11e9-9feb-d96bf7fb857c.png)

* [Numpy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [Sklearn](https://scikit-learn.org/stable/documentation.html/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](https://matplotlib.org/)

# Importando os arquivos de dados

![image](https://user-images.githubusercontent.com/15157510/66668280-3c3eac80-ec2b-11e9-876d-fc8fdf2ef3c4.png)

# Visualizando as Features

![image](https://user-images.githubusercontent.com/15157510/66668434-a2c3ca80-ec2b-11e9-8fc8-9b2efe9c3dc0.png)

# Visualizando a correlação das Features

![image](https://user-images.githubusercontent.com/15157510/66668585-f7674580-ec2b-11e9-9e69-a05090803a78.png)

# Separando as Features importantes

![image](https://user-images.githubusercontent.com/15157510/66668824-7bb9c880-ec2c-11e9-8df1-12c799e97995.png)

# Verificando as Features com valores nulos.

![image](https://user-images.githubusercontent.com/15157510/66668946-d3f0ca80-ec2c-11e9-873b-53e5bd6590c5.png)

# Plotando um gráfico com o relacionamento das Features.

![image](https://user-images.githubusercontent.com/15157510/66669368-b4a66d00-ec2d-11e9-80c3-484975dc9e7d.png)

# Excluíndo dados nulos e com valor zero

![image](https://user-images.githubusercontent.com/15157510/66669870-c89e9e80-ec2e-11e9-8822-8e7e25fa6e2d.png)

![image](https://user-images.githubusercontent.com/15157510/66669896-db18d800-ec2e-11e9-80a7-e9caab13906b.png)

# Verificando se ainda existem valores nulos ou zeros

![image](https://user-images.githubusercontent.com/15157510/66669943-f2f05c00-ec2e-11e9-95e9-4abe646fb12f.png)

# Alterando os valores nulos para zero

![image](https://user-images.githubusercontent.com/15157510/66670243-ae18f500-ec2f-11e9-973f-d6f8e4e74dec.png)

# Armazenando as Features de teste e treino. Iniciando o processo de treinamento do algoritmo.

![image](https://user-images.githubusercontent.com/15157510/66670480-4a42fc00-ec30-11e9-86ca-8d2d5090ac71.png)

# RandomForest

![image](https://user-images.githubusercontent.com/15157510/66670697-c4738080-ec30-11e9-8219-6561583e30b4.png)

# Treinando o algoritmo

![image](https://user-images.githubusercontent.com/15157510/66671332-254f8880-ec32-11e9-8090-e4e05d281a16.png)

# Prevendo os valores na base de teste

![image](https://user-images.githubusercontent.com/15157510/66671401-4617de00-ec32-11e9-902b-110fe5d0c56b.png)

# Visualizando os 10 primeiros registros da predição.

![image](https://user-images.githubusercontent.com/15157510/66671464-6e074180-ec32-11e9-8a6c-a4294f1cd3e1.png)

# Criando um Data Frame com o resultado.

![image](https://user-images.githubusercontent.com/15157510/66671558-ab6bcf00-ec32-11e9-9943-970982197e48.png)

# Criando as colunas no Data Frame de resposta.

![image](https://user-images.githubusercontent.com/15157510/66671619-d6562300-ec32-11e9-85bb-07cc09d06328.png)

# Exportando os resultado para o arquivo desejado no formato CSV.

![image](https://user-images.githubusercontent.com/15157510/66671713-07365800-ec33-11e9-9e7f-46d298cc5465.png)

