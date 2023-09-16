# Добро пожаловать в репозиторий Portal: Galile0 для Лаборантов!

## Скачиваем
Нажимаем `Code -> Download ZIP`, затем перекидываем по пути `C:\Program Files (x86)\Steam\steamapps\sourcemods`\
\
![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/6261fea9-1174-49b5-bf41-285ca1d006b7)
## Установка и настройка Hammer++
Для работы со всем этим в стиме нам надо скачать:
- Portal 2
- Portal 2 Authoring Tools
- Counter-Strike: Global Offensive


Далее скачиваем [Hammer++](https://ficool2.github.io/HammerPlusPlus-Website/download.html) версию для CS:GO, [Link Shell Extension](https://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html#contact)\
Открываем архив `hammerplusplus_build....zip` и перекидываем папку `bin` по пути `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive`\
Затем переходим по пути `C:\Program Files (x86)\Steam\steamapps\common\Portal 2`, выделяем папки `portal2`, `portal2_dlc1`, `portal2_dlc2` ПКМ по ним, выбираем `Запомнить источник ссылки`, преходим в `C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive`, ПКМ по свободному месту `Поместить как... -> Символическая ссылка`\
Папка с CS:GO должна выглядеть примерно так\
\
![268470506-a8fee7ec-500b-4fee-8bac-32090f5382b3](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/4b125e54-4a8d-443f-a762-d72a140a1b31)\
\
Далее открываем Hammer++ и нас будет приветствовать вот такое окно:\
\
![268470538-b8095d3b-f823-46d0-8f08-9128596c4f18](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/d211dc45-7f5a-48a3-b5fc-41b9b76eb864)\
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
![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/ccf816ef-0ccc-45f7-97e3-2cd588b86f27)![изображение](https://github.com/MagicManWithLinux/Portal-Galile0-for-assistants/assets/94105164/bbff70c2-7520-4dd9-9335-a2bbf1cdf6e6)\
\
Всё! Можем спокойно пользоваться Хаммером
## Вопросы и проблемы
Если у вас с чем-то проблемы (Hammer++, GitHub Desktop), то сначала попробуйте прогуглить проблему, затем пишите злому, в случае если проблема не решилась
