Тут файлы с логикой, которые "эмулируют" действия стороны
В текущей реализации, все действия, а именно
- подтвердить начала свапа
- сгенерировать, и отправить секрет
- проверка баланса (доступности нужного кол-ва монет для свапа)

выполняются в коре автоматически
все будет сведено к одному файлу DefaultFlowActions, который ничего не делает
Но может быть в будующем использован для расширения функционала, к примеру свапы на определенную сумму с уведомлением/ручным подтверждением