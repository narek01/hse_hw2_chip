# hse_hw2_chip
 
## [Google Colab]()

## [MultiQC]()
Подрезать чтения не понадобилось

## Stats

Образец | Всего ридов | Выровн. уникально | Выровн. неуникально | Не выровн.
-|-|-|-|-
ENCFF002AAS | 37767437 | 2245315 | 3935318 |31586804
ENCFF002AAR | 37940801 | 1309322 | 4723400 |31908079
ENCFF000VQO | 27422703 | 1347068 | 7498225 |18577410

## Диаграмма Венна

![]()

## Ответы на вопросы

*1. Проанализируйте выдачу bowtie. Почему процент выравниваний получился именно таким?*
Процент выравнивания очень низок, потому что мы картируем чтения не на весь геном, а лишь на одну хромосому. Соответственно, риды, не относящиеся к этой хромосоме, не картировались.

