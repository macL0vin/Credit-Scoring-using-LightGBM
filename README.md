Credit Scoring using LightGBM

Данные: Предоставлены данные по клиентам банка Label = (0/1 вернут/не вернут кредит). Как признаки используется данные по трафику абонента.
Описание задачи:
Исходя из поведения клиентов, необходимо определить надежность клиента (давать или не давать кредит). 
train.csv файл содержит тренировочную выборку, где вам доступен 41 признак пронумерованных в колонках с N_0 по N_40. В колонке Label сохраниться целевое значение.
Вам необходимо определить процент благонадежности для тестовой выборки, которая хранится в файле test_.csv. Где чем ближе к нулю тем надежнее.
В каком формате передать ответ?
Необходимо передать данные в виде csv файла. В котором будет 2 колонки:
ID – соответствующий записи в тестовой выборке (test_.csv)
PRED – вероятность наступления дефолта, значение [0:1]

Пример:

ID      PRED
2154684 0.01
5684654 0.17
3215888 0.06

