Отчет по лабораторной работе №3 "Исследование Cloud Storage" 

Целью работы было ознакомление с основными принципами работы облачного хранилища. В ходе выполнения работы я создала Cloud Storage бакет с именем lab3valieva в регионе us-central1. Затем загрузила в бакет три изображения в форматах jpg и webp. Далее создала папку с именем Vmy-pictures и переместила в нее все загруженные файлы с помощью команды gcloud storage mv. После этого отключила защиту от публичного доступа Public Access Prevention и добавила в настройках бакета принципал allUsers с ролью Storage Object Viewer, что позволило сделать файлы доступными публично. Для каждого файла я сгенерировала публичную ссылку через контекстное меню в консоли и убедилась, что изображения открываются в браузере без авторизации. В завершение работы я удалила бакет lab3valieva со всем содержимым с помощью команды gcloud storage rm --recursive.

<img width="2399" height="1058" alt="image" src="https://github.com/user-attachments/assets/c59d465e-ee01-47ce-9551-3e7652520752" />

<img width="2352" height="1005" alt="image" src="https://github.com/user-attachments/assets/82676771-d99a-4a45-9e75-58fa56c83dec" />

<img width="2217" height="992" alt="image" src="https://github.com/user-attachments/assets/2de3eb1d-1f3c-483f-bc92-aa589cf01f9e" />

<img width="1946" height="1367" alt="image" src="https://github.com/user-attachments/assets/d27a524a-dd81-41ff-b66a-a6a4c37af3b6" />

<img width="1877" height="1191" alt="image" src="https://github.com/user-attachments/assets/db4a5fdc-d7ca-4ab1-baa5-a515e83540c9" />

<img width="2227" height="1367" alt="image" src="https://github.com/user-attachments/assets/20b06db3-b18e-4785-bc3a-26f9f39992b5" />
