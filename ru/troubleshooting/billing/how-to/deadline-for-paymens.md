# До какой даты вносить оплату


## Описание сценария {#case-description}

Нужно выяснить, до какой даты необходимо пополнить баланс платежного аккаунта.

## Решение {#case-resolution}


В Облаке действует постоплатная система расчетов. 

Сумма к оплате складывается из объема потребленных ресурсов Облака за отчетный период.
Саму оплату (пополнение баланса платежного аккаунта) Yandex Cloud ожидает **в течении двух недель с начала нового отчетного периода (месяца)**.

Более подробно цикл оплаты описан в соответствующих разделах документации:

* [Цикл оплаты для юридических лиц](../../../billing/payment/billing-cycle-business.md);
* [Цикл оплаты для физических лиц](../../../billing/payment/billing-cycle-individual.md).

## Если ничего не получилось {#if-issue-still-persists}

Если вышеописанные действия не помогли решить задачу, [создайте запрос в техническую поддержку]({{ link-console-support }}).
При создании запроса укажите следующую информацию:

1. Идентификатор платежного аккаунта.
Он имеет вид `d2nXXXXXXXXXXXXXXXXX`. Этот идентификатор можно найти [на странице с данными по платежному аккаунту]({{ link-console-support }}).
2. Описание проблемы.
