# In Splice Sites

## Теория:

Википедия про сплайсинг: https://en.wikipedia.org/wiki/RNA_splicing https://ru.wikipedia.org/wiki/%D0%A1%D0%BF%D0%BB%D0%B0%D0%B9%D1%81%D0%B8%D0%BD%D0%B3

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Intron_miguelferig.jpg/900px-Intron_miguelferig.jpg" />


## Цель: 

Описать варианты сплайс сайтов среди референсных геномов эукариот.

## Задачи:

1) Создать список референсных геномов NCBI. Базовые данные: мышь и человек.
2) Создать скрипт который на входе берет айди генома, на выходе выдает таблицу информации о сплайс сайтах.
3) Реализивать функциональность конвертации генома и аннотации в набор сплайс сайтов и их фланков с сохранением информации о айди гена.
4) Реализовать функциональность оценки случайности последовательности.
5) Реализовать функциональность оценки фазы экзона.
6) Реализовать функциональность аггрегации статистик по сплайс сайтам внутри генома.
7) Реализовать функциональность аггрегации статистик по сплайс сайтам между геномами.

## Датасет:

Датасет для разработки - геном человека и геном мыши.

Датасте дял анализа рефсек геномы и их аннотация с сайта NCBI.

## Гипотезы для проверки:

1) Сплайс сайты консервативны для ортологов. Классические сплайс сайты доминируют над остальными.
2) Альтернативные сплайс сайты характерны только для опредленных семейств генов.
3) Последовательности фланкирующие сплайс сайты не случайны.
4) Фаза экзона связана с сплайс сайтами.
5) Whereas U2-type introns have been found in virtually all eukaryotes (1) and comprise the vast majority of the splice sites found in any organism, U12-type introns have only been identified in vertebrates, insects, jellyfish and plants (8).

## References

[Comprehensive splice-site analysis using comparative genomics
](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1557818/)

### Branch point site story

[BPP: a sequence-based algorithm for branch point prediction 
](https://academic.oup.com/bioinformatics/article/33/20/3166/3870482)

[Human branch point consensus sequence is yUnAy](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2367711/)

[Wobble Splicing Reveals the Role of the Branch Point Sequence-to-NAGNAG Region in 3′ Tandem Splice Site Selection
](https://journals.asm.org/doi/10.1128/MCB.00363-07)

## Статистика
https://docs.google.com/spreadsheets/d/1WRMZo9Lz_kHDb6NsyeRjyo2zAEBo9w5peZxB169Ref4/edit?usp=sharing
