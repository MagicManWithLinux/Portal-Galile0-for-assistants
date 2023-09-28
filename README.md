# Добро пожаловать в репозиторий Portal: Galile0 для Лаборантов!

## Скачиваем
Нажимаем `Code -> Download ZIP`, затем перекидываем по пути `C:\Program Files (x86)\Steam\steamapps\sourcemods`\
\
![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/8a49d11d-38a5-41f6-9928-351b27127698)
## Установка и настройка Hammer++
Для работы со всем этим в стиме нам надо скачать:
- Portal 2
- Portal 2 Authoring Tools
- Counter-Strike 2 [csgo_demo_viewer]


Для того чтобы скачать Counter-Strike 2 [csgo_demo_viewer], в стиме нажимаем `ПКМ по Counter-Strike 2 -> Бета-версии -> csgo_demo_viewer`\
\
![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/68b96178-a922-42d5-86ec-c5118bd3aec7)\
\
Далее скачиваем [Hammer++](https://ficool2.github.io/HammerPlusPlus-Website/download.html) версию для CS:GO, [Link Shell Extension](https://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html#contact)\
Открываем архив `hammerplusplus_build....zip` и перекидываем папку `bin` по пути `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive`\
Затем переходим по пути `C:\Program Files (x86)\Steam\steamapps\common\Portal 2`, выделяем папки `portal2`, `portal2_dlc1`, `portal2_dlc2` ПКМ по ним, выбираем `Запомнить источник ссылки`, преходим в `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive`, ПКМ по свободному месту `Поместить как... -> Символическая ссылка`\
Папка с CS:GO должна выглядеть примерно так\
\
![268470506-a8fee7ec-500b-4fee-8bac-32090f5382b3](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/369a272a-9fe2-4e72-b295-f8ed0353b725)\
\
Далее открываем Hammer++ и нас будет приветствовать вот такое окно:\
\
![268470538-b8095d3b-f823-46d0-8f08-9128596c4f18](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/185910e9-9049-4b7a-a77e-c86e50053993)\
\
Нажимаем нет, после чего откроется конфигурационное окно\
Выставляем параметры так:
- Configuration
  - `Portal: Galile0-for-assistants`
- Game Data Files
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2\bin\portal2.fgd`
- Game Executable Directory
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2`
- Game Directory
  - `C:\Program Files (x86)\Steam\steamapps\sourcemods\Portal-Galile0-for-assistants`
- Hammer VMF Directory
  - `C:\Program Files (x86)\Steam\steamapps\sourcemods\Portal-Galile0-for-assistants\maps`
- Prefab Directory
  - Можно куда угодно


Далее переходим во вкладку `Build Programms`\
И выставляем так:
- Game Executable
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2\portal2.exe`
- BSP Executable
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2\bin\vbsp.exe`
- VIS Executable
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2\bin\vvis.exe`
- RAD Executable
  - `C:\Program Files (x86)\Steam\steamapps\common\Portal 2\bin\vrad.exe`
- Place compiled maps in this directory before running the game
  - `C:\Program Files (x86)\Steam\steamapps\sourcemods\Portal-Galile0-for-assistants\maps`
 
Всё это должно выглядеть примерно так:\
\
![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/4b9ee6b3-2615-4454-a9a6-3ca735ad39aa)![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/314a4910-6be1-4f34-8196-4773ec36ce1f)\
\
Всё! Можем спокойно пользоваться Хаммером
## Вопросы и проблемы
Если у вас с чем-то проблемы, то сначала попробуйте прогуглить проблему, затем пишите злому (discord: zloy683), в случае если проблема не решилась
