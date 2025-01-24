# Установка

## Игра

Я брал вот эту раздачу: []() - по стандарту: игра, перезагрузка, DLC.

## Программы и утилиты

0. На пункте 4 я радостно обнаружил, что у игры нет привычного менеджера плагинов, погуглил, и понял, что BGS очередной раз осуществило выстрел себе в ~~член~~ногу. Поэтому ставим [https://www.nexusmods.com/site/mods/1](Vortex). Внутри выбираем Skyrim SE.
1. Установить [https://github.com/loot/loot/releases/tag/0.24.1](LOOT). Есть установщик `.exe`, им и воспользовался. Это утилита для настройки порядка загрузки модов. Если его запустить на базовой установке Skyrim AE - покажет кучу советов по проверке установленных модов c xEdit. По идее, в Vortex он подвязывается автоматически.
2. Идём ставить [https://www.nexusmods.com/skyrimspecialedition/mods/164](SSEEdit). Распаковать нужно в папку Skyrim на одном уровне с `Data`. Важно! У меня при запуске показывал кучу ошибок - проблема версии GOG. Исправились с указанием параметров запуска. Для этого надо создать ярлык к `SSEEditQuickAutoClean.exe`, и в его свойствах, в поле `Объект`, добавить ` -I:"C:\Users\unive\OneDrive\Документы\My Games\Skyrim Special Edition GOG\Skyrim.ini"`. Т.е., в итоге должно получиться `"C:\Games\Skyrim Anniversary Edition\SSEEdit 4.1.5f\SSEEditQuickAutoClean.exe" -I:"C:\Users\unive\OneDrive\Документы\My Games\Skyrim Special Edition GOG\Skyrim.ini"`. Тогда будет работать. Дальше очистить все моды по одному.
3. Установить [https://www.nexusmods.com/skyrimspecialedition/mods/30379](Skyrim Script Extender (SKSE64)), проверить версию, как описано на странице nexus.
4. Установить 