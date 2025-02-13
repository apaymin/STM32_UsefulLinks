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

# I2C

1. [Настройка и использование I2C](https://microtechnics.ru/stm32-i2c-nastrojka-i-primer-ispolzovaniya-shiny-i2c/).

# USB

1. [AN4879](https://www.st.com/resource/en/application_note/an4879-introduction-to-usb-hardware-and-pcb-guidelines-using-stm32-mcus-stmicroelectronics.pdf) - Introduction to USB hardware and PCB guidelines using STM32 MCUs
2. [USB in a Nutshell](https://www.beyondlogic.org/usbnutshell/usb2.shtml)
3. [Подтяжка с транзистором](https://community.st.com/t5/stm32-mcus-embedded-software/stm32f103-usb-circuit/td-p/424454)
4. [Подтяжка с транзистором, русский форум](http://forum.easyelectronics.ru/viewtopic.php?f=14&t=15396)
5. [Загрузка прошивки по USB](stm32-dfu.md) - собрал небольшой гайд с использованием проприетарного решения (не требует собственного bootloader'а)



# Отладка

[Настройка отладки по SWO в Keil](swo_keil.md) - собрал информацию с нескольких сайтов и свёл в одну статью способ, работающий у меня

## DIY ST-Link

1. [DIY-программатор ST-Link V2.1 с Хабра](https://habr.com/ru/articles/749474/)
2. [DIY ST-Link](https://stm32world.com/wiki/DIY_STM32_Programmer_(ST-Link/V2-1))
3. [Дампы прошивки](https://github.com/Krakenw/Stlink-Bootloaders)
4. Реверс-инжиниринг прошивки ST-Link: [часть 1](https://lujji.github.io/blog/reverse-engineering-stlink-firmware/) и [часть 2](https://lujji.github.io/blog/reverse-engineering-stlink-firmware-part2/)
5. [Использование Black Magic Debug](https://lujji.github.io/blog/installing-blackmagic-via-stlink-bootloader/) - иснтрукция по установке ПО для отладки STM32 на ST-Link




# Настройка среды

## VSCode + CMake

1. [Использование ST'шного расширения для VSCode](https://zenembed.com/ru/vscode-cubemx-guide)
2. [Использование только CMake](https://zenembed.com/ru/vscode-cubemx-pro-guide)

## Keil + STM32CubeMX

1. [STM32CubeIDE -> STM32CubeMX -> Keil](https://www.keil.com/appnotes/files/apnt_323.pdf) - удобная , но костыльная миграция из CubeIDE в Keil  
2. [Установка пакетов для Keil](https://www.eng.auburn.edu/~nelsovp/courses/elec2220/arm_keil/Install_ARM_MDK_and_PACKS.pdf)
3. [Пакет для STM32F4](https://www.keil.arm.com/packs/stm32f4xx_dfp-keil/overview/)
