# cycle-turn-signals-on-arduino - Конструкция для больших выходных и длинного лета.
В скетчах настраиваются следующие переменные:

#define   TURN_LEFT_PIXEL_NUM    21 // количество светодиодов на одной стороне.

#define   TURN_PICTURE_NUM     95 // кол-во картинок (фраймов) в мультике поворотов.

#define   STOP_PICTURE_NUM     1 // кол-во картинок (фраймов) в мультике стоп сигналов.

#define   TURN_BACKGROUND      ((uint32_t) 0x00010000) // цвет и яркость габаритов. Фон поворотников.

#define   STOP_ACTIVE_COLOR    ((uint32_t) 0x15FF0000)  // цвет и яркость сигнала стоп.

#define   STOP_ACTIVE_COLOR2   ((uint32_t) 0x025F0000) // цвет и яркость сигнала стоп2.

#define   TURN_ACTIVE_COLOR    ((uint32_t) 0x0F5F1300) // цвет и яркость поворотников.

#define   TURN_INDICATOR_COLOR ((uint32_t) 0x00090300) // цвет и яркость поворотников на повторителе.

#define   STOP_INDICATOR_COLOR ((uint32_t) 0x00100000) // цвет и яркость стопа на повторителе.

#define   TURN_SHOW_DELAY      30 // время смены кадров поворотников

#define   STOP_SHOW_DELAY      180 // время смены кадров стоп сигналов
