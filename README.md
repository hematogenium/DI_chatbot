Сценарий чатбота для игры «Быки и коровы»

**Начало игры**
  Чатбот: «Привет! Хочешь поиграть в игру «Быки и коровы»? Я задумал тайное четырёхзначное число с неповторяющимися цифрами. Твоя задача — отгадать это число.» #Приветствие
  if Пользователь: «Да» #Cогласие пользователя, начало игры
  elif Пользователь: «Нет» #Отказ пользователя, выход из игры
  
**Ход игры**
  Чатбот: «Хорошо, давай начнём! Попробуй отгадать моё число, сообщив свою попытку.» #Запрос на попытку
  Пользователь: «Моя попытка — 1234.» #Сообщение попытки
  #Чатбот анализирует попытку пользователя и определяет количество «коров» (цифр, угаданых на неверных позициях) и «быков» (цифр, угаданых вплоть до позиции)
  Чатбот: «В твоей попытке две «коровы» (цифры «1» и «2») и два «быка» (цифры «3» и «4»).» #Ответ чатбота
  #Пользователь делает новую попытку, сообщая чатботу другое четырёхзначное число

**Завершение игры**
  # Игра продолжается до тех пор, пока пользователь не отгадает тайное число чатбота или не сдастся
  Чатбот: «Поздравляю! Ты отгадал моё число!» #Победа пользователя
  Чатбот: «Жаль, что ты не смог отгадать моё число. Хочешь сыграть ещё раз?» #Поражение пользователя
    if Пользователь: «Да» #Согласие пользователя, начало игры
    elif Пользователь: «Нет» #Отказ пользователя, выход из игры
