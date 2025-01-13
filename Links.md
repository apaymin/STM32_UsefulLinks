# Полезные ссылки для STM32

# CAN

## bxCAN (для F4 и младше)

1. [Time quants и банки фильтров](https://microtechnics.ru/stm32-i-protokol-can-nastrojka-v-stm32cubemx/)

2. [Первоначальная настройка CAN с прерываниями](https://istarik.ru/blog/stm32/159.html) 

3. [Ещё один пример работы с фильтрами](https://istarik.ru/blog/stm32/160.html)

4. [Онлайн-калькулятор предделителя для тактирования CAN](http://www.bittiming.can-wiki.info/?ctype=bxCAN&CLK=8&calc=1&SJW=1) - уже посчитано для 8 МГЦ тактовой частоты

# FSMC/FMC

## MRAM

1. [Осбенности работы с MRAM](https://community.st.com/t5/stm32-mcus-products/stm32f437-external-memory-interface/td-p/474693) - write recovery time в STM ровно 1 FMC/FSMC clock cycle, а для MRAM равно 12 нс

# HAL

1. [UM1725](https://www.st.com/resource/en/user_manual/um1725-description-of-stm32f4-hal-and-lowlayer-drivers-stmicroelectronics.pdf) - HAL и LL для STM32F4

# USB

1. [AN4879](https://www.st.com/resource/en/application_note/an4879-introduction-to-usb-hardware-and-pcb-guidelines-using-stm32-mcus-stmicroelectronics.pdf) - Introduction to USB hardware and PCB guidelines using STM32 MCUs

2. [USB in a Nutshell](https://www.beyondlogic.org/usbnutshell/usb2.shtml)

3. [Подтяжка с транзистором](https://community.st.com/t5/stm32-mcus-embedded-software/stm32f103-usb-circuit/td-p/424454)

4. [Подтяжка с транзистором, русский форум](http://forum.easyelectronics.ru/viewtopic.php?f=14&t=15396)

# Отладка

[DIY-программатор ST-Link V2.1 с Хабра](https://habr.com/ru/articles/749474/)

[DIY ST-Link](https://stm32world.com/wiki/DIY_STM32_Programmer_(ST-Link/V2-1))