# Начало Работы

Мы рады, что Вы выбрали наш редактор. Давайте начнем прямо сейчас! :tada:

- Установите `g++` / `python` / `java` в зависимости от используемого языка. Убедитесь, что они находятся в системном пути(PATH), чтобы Вы могли запускать их непосредственно в командной строке. Также вы можете установить команды компиляции в настройках, если они не находятся в пути(PATH).

- Установите настройки в Настройках (параметры -> настройки, или используйте сочетание клавиш <kbd>Ctrl+P</kbd>).

- Если вы хотите парсить примеры тестовых наборов с таких онлайн-платформ, как Codeforces, пожалуйста, установите [Competitive Companion](https://github.com/jmerle/competitive-companion) в Ваш браузер.

- Если вы хотите послать решение Codeforces в Editor, пожалуйста, установите [CF Tool](https://github.com/xalanq/cf-tool). Если он не находится в системном пути(PATH), вы можете установить путь к нему в Preferences->Extra->Misc->CF Tool Command. Не забудьте настроить его с помощью `cf config` (выберите пользователя и шаблон).

- Если вы хотите сделать форматирование своего C++ кода, вам нужно установить [Clang Format](http://releases.llvm.org/download.html). вы должны убедиться, что он установлен на системном пути(PATH) или установить путь к нему в Preferences->Formatting->Clang Format Command.

# Советы

## CF tool

Вы можете парсить задачу через Competitive Companion, либо вставить URL-адрес задачи через меню вкладок правой кнопкой мыши. Затем вы увидите кнопку "Sumnit". Кнопка доступна только тогда, когда CF Tool будет найден редактором. Вы можете установить путь к нему в Preferences->Extra->Misc->CF Tool Command.

## Для пользователей Java

Вы должны использовать **non-public** класс с именем **a** для вашего решения.

## Персональные настройки

### Быстрое сохранение файлов

Если эта опция включена, [QFile](https://doc.qt.io/qt-5/qfile.html) всегда будет использоваться для сохранения файлов, в противном случае [QSaveFile](https://doc.qt.io/qt-5/qsavefile.html) будет использоваться в некоторых ситуациях.

Включите эту опцию, чтобы сохранить файлы быстрее, но если ошибка произойдет при записи файла, есть вероятность потерять как и в старый, так и в новый файлы. Обратите внимание, что старый файл не будет потерян, когда редактор не имеет разрешения на файл. Эта ошибка происходит крайне редко.

### Аргументы выполнения

Это аргументы, передаваемые вашим программам в командной строке при их запуске. Обычно их не нужно дополнительно устанавливать.

### Clang Format

Содержание параметра "Clang Format Style" совпадает с содержанием файла `.clang-format`. Вы можете почитать об этом [здесь](https://clang.llvm.org/docs/ClangFormat.html).

### Горячие клавиши

Вы можете использовать <kbd>Ctrl+S</kbd>, </kbd>Ctrl+N</kbd>, </kbd>Ctrl+D</kbd>, <kbd>Ctrl+R</kbd> для `сохранения`, `создания`, `удаления` и `переименования` файла.

## Ярлыки

Кроме ярлыков в меню, вы можете использовать [только для чтения привязки клавиш](https://doc.qt.io/qt-5/qtextedit.html#read-only-key-bindings) и [редактирование привязок клавиш](https://doc.qt.io/qt-5/qtextedit.html#editing-key-bindings). Также есть некоторые скрытые ярлыки: <kbd>Tab</kbd>(когда есть выбор) и <kbd>Shift+Tab</kbd> для отступа и обратного отступа, <kbd>Ctrl+Enter</kbd> и <kbd>Ctrl+Shift+Enter</kbd> для вставки строки до и после, <kbd>Shift+Delete</kbd> для удаления текущей строки.

## Перетаскивание

Вы можете перетащить файлы и поместить их в главный редактор, а также входные и выходные данные тестовых наборов.

## Вкладки

Вы можете использовать клавиши <kbd>Ctrl+Tab</kbd> и <kbd>Ctrl+Shift+Tab</kbd>  для переключения на следующую / предыдущую вкладку.

Вы можете щелкнуть правой кнопкой мыши на вкладках, чтобы получить дополнительное контекстное меню. Содержание меню основано на том, является ли эта вкладка без названия или нет, имеет проблемный URL или нет.

## Testcases

Кейсы Testlib компилируются при смене кейса или изменении настроек, поэтому вам, возможно, придется подождать минуту перед запуском.

Вы можете загружать тестовые наборы из файлов и редактировать тестовые наборы в больших окнах в контекстном меню тестовых наборов.

Вы можете щелкнуть на вердикт, чтобы открыть средство просмотра различий.

## Режим просмотра

Режим просмотра помогает сосредоточиться на вашем коде, исследовать выходные данные, ошибки или сделать редактор более узким, чтобы вы могли разделить экран на две части.

Вы можете установить горячую клавишу для переключения режимов просмотра в настройках.

## Запустите редактор CP в командной строке

Редактор CP поддерживает некоторые параметры командной строки, запустите `cpeditor --help` для получения дополнительной информации.

Лучше использовать Linux-подобные оболочки, такие как git bash на Windows.

Несуществующий файл можно открыть как вкладку (и сохранить в пути позже) в командной строке или открыть все файлы C++ в каталоге рекурсивно.
