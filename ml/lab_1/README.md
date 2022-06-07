# spring_2022

Laboratório nº 1: Pré-processamento de dados
O objetivo do trabalho de laboratório é adquirir habilidades para trabalhar com bibliotecas para análise de dados, pré-processamento de dados e ferramentas de visualização.
Notas:
1. Se você colocar um arquivo de dados na pasta ":\WinPython-64bit-3.5.4.0Qt5\notebooks\", não será necessário especificar o caminho para esse arquivo ao carregá-lo usando a função pandas.read_csv.
2. O processamento de arquivos csv grandes pode ser feito em partes:
tamanho do pedaço=10**6
for chunk em pd.read_csv(filename, chunksize=chunksize):
    processo (pedaço)

3. Você não precisa usar loops para processar dados ao fazer o laboratório. Use as funções da biblioteca Pandas.

4. Comando para instalação separada de bibliotecas:

pip install numpy scipy matplotlib ipython jupyter pandas sympy nose spyder seaborn

5. Lendo as primeiras linhas de um arquivo:
read_csv(..., nrows=999999)

6. A tarefa "Mercado de carros secundários" - para abrir um conjunto de dados, você precisa abrir o conjunto de dados com o parâmetro encoding='iso-8859-1'


---------------------------------------------------------------------------------------------------------------------------


Лабораторная работа № 1. Предварительная обработка данных
	Цель лабораторной работы – получение навыков работы с библиотеками анализа данных, предварительной обработки данных, средствами визуализации.
Замечания:
1. Если разместить файл с данными в папке «:\WinPython-64bit-3.5.4.0Qt5\notebooks\» при его загрузке с помощью функции pandas.read_csv не нужно указывать путь к данному файлу. 
2. Обработку больших csv файлов можно выполнять по частям:
chunksize = 10 ** 6
for chunk in pd.read_csv(filename, chunksize=chunksize):
    process(chunk)

3. При выполнении лабораторной работы для обработки данных не нужно использовать циклы. Используйте функции библиотеки Pandas.

4. Команда для отдельной установки библиотек:

pip install numpy scipy matplotlib ipython jupyter pandas sympy nose spyder seaborn

5. Чтение первых нескольких строк из файла:
read_csv(..., nrows=999999)

6. Задание «Вторичный рынок машин» - открывать набор данных нужно открывать набор с параметром encoding='iso-8859-1'
