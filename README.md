# payments-landing-page

# API

В URL передать параметр payment_result формата:
```
{
   "status":{
      "success":true/false,
      "message":"если ошибка добавить сюда причину ошибки"
   },
   "receiver":"имя организации",
   "amount":"сумма оплаты",
   "date": "timestamp",
   "payer":{
      "firstName":"Максим",
      "secondName":"Смагин",
      "thirdName":"Олегович"
   },
   "transactionNumber": "номер транзакции в нашей бд"
}
```
