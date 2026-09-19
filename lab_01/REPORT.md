# Задание 1
## 1 
  ### В REPL результат любого выражения показывается автоматически, а при запуске файла в терминале не отображается результат вычислений, так как в файле не содержалось команды отобразить результат 
   #### <img width="860" height="796" alt="image" src="https://github.com/user-attachments/assets/8e611dca-8d30-42bb-8040-f8d7a16ffe3f" /> 
    
### Для того, чтобы при запуске файла результат отобразился в терминале нужно добавить функцию print 
  #### <img width="946" height="821" alt="image" src="https://github.com/user-attachments/assets/26bacb16-4313-4780-a6bf-8685fa5302ec" />


## 2
  ### <img width="473" height="181" alt="image" src="https://github.com/user-attachments/assets/05c7861b-aad8-41c0-8cfb-0af8d384e5d6" />
   #### Выражениями являются фрагменты 4 * 2, "Python" и f"{course}: {hours} часов"
   #### Инструкциями являются все строки кода
   #### Литералы: "Python", 4, 2, f"{course}: {hours} часов"
   #### Создающиеся имена: course и hours


## 3
  ### Версия интерпретатора: Python 3.12.3
   #### <img width="758" height="57" alt="image" src="https://github.com/user-attachments/assets/e4aafee3-f12d-42d1-b498-1b5f47729ffd" />

  ### Узел присваивания: Assign
  ### Узел арифметической операции: BinOp
   #### <img width="420" height="199" alt="image" src="https://github.com/user-attachments/assets/5cef7068-1695-43a7-b15c-fc7937056a0b" />
  ### Узел вызова print(): Call
   #### <img width="482" height="95" alt="image" src="https://github.com/user-attachments/assets/4718cc55-1ab0-4d5a-a0b4-8e907e3fecf7" />

  ### Инструкция, отвечающая за загрузку константы: LOAD_CONST
  ### Инструкция, отвечающая за вызов функции: CALL
   #### <img width="860" height="309" alt="image" src="https://github.com/user-attachments/assets/351c98b2-3a3b-4fd2-be64-6513f27bee54" />

  ### Байткод CPython нельзя считать машинным кодом процессора потому что байткод выполняется не процессором напрямую, а виртуальной машиной python.


# Задание 2
  ### Прогнозы сравнений:
   #### 1) True 
   #### 2) True
   #### 3) True
   #### 4) False
   
  ## 1.
```mermaid
graph LR
  a["a"] --> obj1["1000"]
  b["b"] --> obj1
  c["c"] --> obj2["1000"]
style obj1 fill:yellow
style obj2 fill:red
```
  ## 2. 
   ### При проверке на равенство элементов сравнивается их значение, а при проверке на идентичность проверяется, ссылаются имена на один объект в памяти или на разные
  ## 3. 
   ### <img width="511" height="307" alt="image" src="https://github.com/user-attachments/assets/9f950b00-715b-4290-b846-a14de66bf3f9" />
  ## 4. 
   ### В python одинаковые строковые литералы хранятся в памяти в единственном экземпляре, операция конкатенации строк выполняется на этапе компиляции
   #### <img width="909" height="494" alt="image" src="https://github.com/user-attachments/assets/fd663608-c2a1-4d83-80a0-50fb1b9f8ad3" />
  ## 5. 
   ### == нужно использовать для сравнения значений, а is для проверки на идентичность
  ## Контрольные вопросы:
   ### 1) Инструкция b = a не создаёт копию объекта, а создаёт новое имя b, которое ссылается на ту же ячейку в памяти, что и a
   ### 2) type() возвращает тип объекта, имя которого указано в скобках, id() возвращает число, представляющее адрес объекта в памяти
   ### 3) None принято сравнивать с помощью is, так как все переменные None ссылаются на один и тот же объект
# Задание 3
 ## 




