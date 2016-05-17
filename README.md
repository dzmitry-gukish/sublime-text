sublime-text-rus
================

##Preferences.hukishd.sublime-settings
Настройки с русским описанием. Найдено на ресурсе по адресу http://sublimetext.ru/documentation/preferences/list 
   
Особенность - все комментарии (строки с //) теряются после сохранения или изменения каких-либо настроек через меню. Логично, поскольку JSON не может содержать комментарии. 
   
Во-вторых, такое ощущение, что только измененные (по сравнению со значениями по умолчанию) настройки читаются и хранятся где-то в памяти, а потом файл настроек начисто перезаписывается. 

Файл настроек предназначен для версии ~~3047~~ 3065. ~~Планирую сделать для текущей версии 3059 - есть несколько дополнительных пунктов~~. Версии 3083 и 3080 не содержат заслуживающих внимания настроек.

3059
+ enable_tab_scrolling: [true|false]
+ show_encoding: [true|false] 
  show_line_endings: [true|false] - to encoding and line endings
+ caret_extra_top: [num]
  caret_extra_bottom: [num]
  caret_extra_width: [num] - to __control the caret size__
+ index_exclude_patterns: [num] - to setting to control which files get indexed
+ minimap_scroll_to_clicked_text

3065
+ remember_full_screen: [true|false]

3080
+ spelling_selector - список переключателей проверки правописания
+ remember_open_files: [true|**false**] - изменено значение по умолчанию.
+ auto_complete_cycle: [true|**false**] - поведение списка автозамены. Если false - при нажатии кнопки "вверх" окно выбора автозамены исчезает, иначе переходит на последний элемент.

3083
+ index_workers: [num] - number of threads used for file indexing. By default **0** - then equal the number of CPU cores. 

3103
+ ничего в настройки

3114
+ ничего в настройки

##MyHotkeys.sublime-keymap
Настройки хоткеев автозамены символов табуляции на символы пробелов (обычно 4, указано в .sublime-settings в параметре tab_size) и наоборот - 4 пробела на табуляцию.
