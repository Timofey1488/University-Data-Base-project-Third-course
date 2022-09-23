# Лабораторные работы по СУБД
### ФИО: Сидоренко Тимофей Сергеевич
### Номер группы: 053505

### Функциональные требования

а)Авторизация пользователей  
б)Управление пользователями  
с)Система ролей  
Система ролей будет состоять из:  
    * Клиента  
      Сможет покупать товары, взаимодействовать с корзиной, оформлять заказ, заполнять платежные данные  
    * Менеджера по продажам  
      Сможет отслеживать ближайшие поставки, добавлять товар, удалять товары, которые не в наличии, просматривать список накладных по продуктам,   
      может получить сводку по всем товарам  
    * Админа  
      Сможет редактировать контент, но не может покупать товары от своего лица  
    * Неавторизированного пользователя  
      Может только просматривать контент, но никак с ним не взаимодействовать  
d)Журналирование  действий пользователя  
Логирование будет происходить каждый раз когда пользователь работает с CRUD  
    
