# О продукте

Устройства компании Solar Control предназначены для управления, мониторинга, и охраны домашних и частных СЭС.
Сбор метрик, выдача информации по основным параметрам инвертора, уведомления во время изменения статуса, и произошедших 
аварий 
Программно-аппаратное решение состоит из устройства, которое непосредтсвенно подключается к солнечному инвертору для 
работы с ним по протоколу [MODBUS](modbus.md), и специального программного обеспечения (мобильное приложение, телеграм-бот)

Аппаратная часть основана на использовании микрокомпьютеров [Raspberry Pi](https://www.raspberrypi.org)

Программная часть - использование Telegram [TdLib](https://core.telegram.org/tdlib) 
для обмена сообщениями, хранения данных, отправки видео и изображений прямо с устройства