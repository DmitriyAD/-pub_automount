Данный репозиторий предназначен для автоматизированной настройки принтера, чтобы он работат с FLASH-накопителями.
Предназначение файлов:
automount - главный файл, с помощью которого можно произвести настройку. Содержит в себе все команды для настройки.
99-local.rules - правило для перехвата события подключения накопителя.
usb-mount@.service - служба для слежения за подключенными устройствами.
usb-mount.sh - файл сценария. В нем храниться сценарий действий при подключении или отключении накопителя.
