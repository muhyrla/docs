{% note info %}

Поскольку проекты запускаются на разных платформах {{ yandex-cloud }} с разными вычислительными мощностями, {{ ml-platform-name }} не гарантирует доступность 100% объема оперативной памяти.

{% endnote %}


Имя | Количество vCPU | Количество GPU | RAM, ГБ
---- | ---- | ---- | ----
**Конфигурации с vCPU на [платформе Intel Ice Lake](../../../compute/concepts/performance-levels.md)**
**c1.4** (по умолчанию) | 4 | 0 | 32
**c1.8** | 8 | 0 | 64
**c1.32** ^1^ | 32 | 0 | 256
**c1.80** ^2^ | 80 | 0 | 640
**Конфигурации с vCPU на [платформе Intel Broadwell](../../../compute/concepts/performance-levels.md) и GPU [NVIDIA® Tesla® V100](../../../compute/concepts/gpus.md)**
**g1.1** | 8 | 1 | от 48 до 96
**g1.2** | 16 | 2 | от 96 до 192
**g1.4** ^1^ | 32 | 4 | от 192 до 384
**Конфигурации с vCPU на [платформе AMD EPYC™](../../../compute/concepts/gpus.md) и GPU [NVIDIA® Ampere® A100](https://www.nvidia.com/ru-ru/data-center/a100/)**
**g2.1** ^1^ | 28 | 1 | 119
**g2.2** ^1^ | 56 | 2 | 238
**g2.4** ^1^ | 112 | 4 | 476
**g2.8** ^2^ | 224 | 8 | 952
**Конфигурации с vCPU на платформе [Intel Ice Lake](../../../compute/concepts/performance-levels.md) и GPU [NVIDIA® Tesla® T4](https://www.nvidia.com/ru-ru/data-center/tesla-t4/)**
**gt4.1** ^1^ | 4 | 1 | 16


^1^ доступна после пополнения баланса платежного аккаунта на сумму не менее 500 ₽ или по запросу в техническую поддержку.

^2^ доступна только для юридических лиц, индивидуально по запросу в техническую поддержку.


