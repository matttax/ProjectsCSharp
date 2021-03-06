**Приложение, позволяющее управлять обширной номенклатурой товаров, хранимых на складе.**<br><br>
Поскольку на складе могут храниться самые разные товары, их нужно классификацировать. Самый удобный классификатор – это древовидная структура, где каждый узел – раздел, который описывается, как минимум, названием и может содержать товары. В классификаторе не может быть двух одноименных разделов, имеющих общего родителя.
Товар описывается набором обязательных характеристик (наименование, артикул, цена, остаток на складе)<br><br>
Функциональность:
1. Вывод и управление классификатором, включая: создание разделов классификатора, изменение, удаление.
2. Вывод списка товаров в разделе и управление товарами с обязательным набором характеристик, включая: создание товара (с привязкой к разделу классификатора), изменение, удаление.
3. Сохранение состояния склада в текстовый файл и загрузка состояния склада оттуда по запросу пользователя.
4. Создание CSV-отчета (пригодного для загрузки в Excel), в котором содержится список товаров, заканчивающихся на складе и поэтому требующих дозаказа у поставщиков (т.е. товаров, количество которых меньше заданного пользователем приложения значения).
5. Отображение товаров, расположенных во всех подразделах данного раздела (т.е. “ниже” в классификаторе). Товары из подразделов выделяются в списке, чтобы была возможность отличить их от товаров расположенных непосредственно в текущем разделе.
6. Возможность автоматической генерации классификатора и товаров по заданным пользователям параметрам, включающим количество разделов классификатора и количество товаров.
