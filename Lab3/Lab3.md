﻿**Прецедент “Начать игру”**

![](Aspose.Words.b2b8e85c-3268-4c61-b847-194940f9dd3b.001.png)

|**Операция**|**Выбор количества игроков**|
| :-: | :-: |
|Ссылки|Прецедент: Начать игру|
|Предусловие|Игрок запустил игру|
|Постусловие|Отображение меню выбора количества игроков|

|**Операция**|**Выбор минимального значения** |
| :-: | :-: |
|Ссылки|Прецедент: Начать игру|
|Предусловие|Игрок выбрал количество игроков|
|Постусловие|Минимальное значение записано в систему|




**Прецедент “Начать раунд”**

![](Aspose.Words.b2b8e85c-3268-4c61-b847-194940f9dd3b.002.png)

|**Операция**|**Перевод игрока за игровой стол**|
| :-: | :-: |
|Ссылки|Прецедент: Начать раунд|
|Предусловие|В системе содержится информация о количестве игроков и минимальном значении|
|Постусловие|Перевод игрока за игровой стол|











**Прецедент “Сделать ход”**

![](Aspose.Words.b2b8e85c-3268-4c61-b847-194940f9dd3b.003.png)

|**Операция**|**Выполнение хода**|
| :-: | :-: |
|Ссылки|Прецедент: Сделать ход|
|Предусловие|Игрок находится за игровым столом|
|Постусловие|Ход игрока выполнен|








**Прецедент “Бросить кость повторно”**

![](Aspose.Words.b2b8e85c-3268-4c61-b847-194940f9dd3b.004.png)

|**Операция**|**Выполнение повторного броска**|
| :-: | :-: |
|Ссылки|Прецедент: Бросить кость повторно|
|Предусловие|Игрок находится в игре и сходил один и более раз|
|Постусловие|Ход игрока выполнен|







**Прецедент “Передать ход”**

![](Aspose.Words.b2b8e85c-3268-4c61-b847-194940f9dd3b.005.png)

|**Операция**|**Передача хода**|
| :-: | :-: |
|Ссылки|Прецедент: Передать ход|
|Предусловие|Игрок находится в игре и сходил один и более раз|
|Постусловие|Передача хода следующему игроку |

