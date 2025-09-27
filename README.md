# Prognosis model

Прогнозная модель, направленная на прогнозирование нагрузки на сервис с учетом дневной сезонности. В будущем будет добавлен модуль сезонности по месяцам и возможность закладывать релизы. 

В папке 3 файла:
prognosis_model.ipynb - сам блокнот с модель,
load_data_aht.xlsx - нагрузка по дням с aht,
load_data.xlsx - нагрузка по интервалам в 15 минут по очередям.

Указываем экселевские исходники в соответствующие пути:
<img width="2150" height="356" alt="image" src="https://github.com/user-attachments/assets/074d6007-11dc-4769-b6d2-ccac0cdb575e" />
Запускаем скрипт, получаем прогноз по дням с недельной сезонностью:
<img width="2276" height="609" alt="image" src="https://github.com/user-attachments/assets/e33ae7a2-d8b7-43ed-bab9-5d1e803f1c43" />
А также прогноз по по интервалам в 15 минут в течение дня:
<img width="2345" height="1204" alt="image" src="https://github.com/user-attachments/assets/d094838a-ceb2-45c6-b0af-cccee9271478" />
