# ESP32-Energy-monitor

Возможности Монитора потребляемой энергии дома

Получать такие параметры:

- Температура;
- Влажность;
- Напряжение питания;
- Силу тока;
- Потребляемую мощность.

Просмотр параметров через:

- Локальный веб-сервер;
- Дисплей.

Дополнительные возможности:

- Строить графики потребления;
- Вычислять стоимость;
- Считать общее потребление за месяц(в конце месяца счетчик сбрасывается) Kwh;
- Показывать рельную потребяемую мощность и предпологаемую;
- Смена пароля роутера в Веб-интерфейсе, без перепрошивки всего устройства.

Локальный веб сервер

![изображение](https://user-images.githubusercontent.com/94782611/154678362-1deff3f1-8407-485f-8860-b62a47340bb0.png)

Дисплей 

![изображение](https://user-images.githubusercontent.com/94782611/153896403-3878c9dc-cc06-4949-9f7b-9cdad9dd88a4.png)

Принципиальная схема

Резистор R2 = 33 Ома

![Schematic_Счетчик 3 0_2022-02-14](https://user-images.githubusercontent.com/94782611/153902685-d3e00f8d-ae83-437c-b5f4-f543981a8c6a.png)
[Schematic_Счетчик 3.0_2022-02-14.pdf](https://github.com/SimonW0rk/ESP32-Energy-monitor/files/8062311/Schematic_.3.0_2022-02-14.pdf)

Монтажная плата

![изображение](https://user-images.githubusercontent.com/94782611/153896806-5a3d23cd-d76b-479e-b4a0-95079617ca6e.png)

Готовое устройство

![photo_2022-02-14_17-51-51](https://user-images.githubusercontent.com/94782611/153898464-1d66357b-c998-45cb-81a7-a27eed2979c6.jpg)

Датчик STC-013-000

![изображение](https://user-images.githubusercontent.com/94782611/153898662-b9f4f0f9-e09a-4cce-9f98-3da64be6bf8a.png)

Список нужных компонентов:

- Микроконтролер ESP32;
- Неинвазивный датчик силы тока 100А STC-013-000;
- Дисплей SSD1306 OLED 128x64;
- Датчик температуры и влажности DHT11;
- Датчика переменного напряжения ZMPT101B;
- Линейный стабилизатор L7805CV;
- Коденсаторы электролитические на 10 мкФ, 100мкФ;
- Конденсаторы керамические на 33мкФ, 10мкФ;
- Резисторы на 33 Ома, 100 кОм, 220 кОм.
