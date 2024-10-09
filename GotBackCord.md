# Обход блокировки Discord с рабочим Войсом (GoogleColab)
### Качаем софт
Тут все просто, тупо качаем софт для туннелирования трафика с [Github](https://github.com/amnezia-vpn/amneziawg-windows-client/releases/download/1.0.0/amneziawg-amd64-1.0.0.msi).
### Качаем файл конфигурации
1. Перейти на [Colaboratoty](https://colab.research.google.com/)
2. Долистать до любого терминала
3. Вставить туда поочередно и запустить:
```python
pip install google-colab-shell
```
```python
from google_colab_shell import getshell
```
```python
getshell()
getshell(height=400)
```
4. Откроеться терминал в терминале. В новое окно терминала вставляем и ждем:
```batch
curl -sSL https://raw.githubusercontent.com/ImMALWARE/bash-warp-generator/main/warp_generator.sh | bash
```
5. Переходим по сгенерировавшейся ссылке (если не жмется, копируем и вставляем в адресную строку ручками) и качаем файл `WARP.conf` (Загрузка начнется автоматически)
### Запуск софта
1. Запускаем Амнезию (Софт для туннелирования трафика)
2. Импортируем ранее скаченный конфиг
3. Жмём `Подключить`
---