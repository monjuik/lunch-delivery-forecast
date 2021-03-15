# Прогноз времени доставки обеда

На основании прошлых данных стоится модель для прогнозирования времени доставки обеда. 

Анализируемые данные (из data.csv):
1. `weekday` — день недели,
1. `preholiday` — предпраздничный день,
1. `rainfall` — количество осадков в мм,
2. `temperature` — температура Цельсия,
3. `manager` — номер офис-менеджера,
4. `service` — номер сервиса доставки.

Для прогноза используется Random Forest, ссылки для чтения:
1. [Random Forest in Python](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0),
2. [Случайный лес (Random Forest)](https://dyakonov.org/2016/11/14/случайный-лес-random-forest/).

## Подготовка окружения

1. Установите [Anaconda Individual edition](https://www.anaconda.com/products/individual),
2. У меня она отказывалась обновлять модули и ставить новые, поэтому я делал это через [miniconda](https://docs.conda.io/en/latest/miniconda.html#macosx-installers):
   3. `conda install pandas`,
   4. `conda install pydot`,
5. Запустите Anaconda Navigator,
6. Запустите Jupyter Notebook,
7. Используйте приложенный `slq-lunch.ipynb`.
