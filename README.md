# Волки на побережье

Здесь вы найдёте перевод материалов для кампэйна Wolves Upon the Coast --- "Волков на побережье" --- на русский язык.

Все материалы соответствуют **release-april**

## Полезные ссылки

https://lukegearing.itch.io/wolves-upon-the-coast-grand-campaign --- собственно гекскроул с демкой

https://lukegearing.itch.io/volume-2-monsters --- монстрятник

https://lukegearing.itch.io/treasure --- сокровища

https://itch.io/s/72555/wolves-gc-volume-2-treasure --- бандл с 3 позициями выше

https://assemblyrequisite.itch.io/wolves-upon-the-coast-asset-pack --- кастомный чарник и карта для игроков

https://lukegearing.blot.im/wolves-upon-the-coast-hexfill-procedure --- процедура заполнения гексов

https://www.timeanddate.com/calendar/?year=850&country=9 --- календарь

## Генераторы

https://perchance.org/wutc-chargen --- генератор персонажей

https://perchance.org/2bt3luh939 --- генератор имён

https://blog.reedsy.com/character-name-generator/medieval/ --- генератор имён №2

https://perchance.org/wutc-encounters --- генератор столкновений (а также погоды)

https://perchance.org/wutc-treasure ---- генератор сокровищ

# В планах

- Перевод
  - treasure-special.md
  - wandering-isles.md

# Pandoc

pandoc 3.1.2  
XeTeX 3.141592653-2.6-0.999993 (TeX Live 2021)

ПДФки сделаны из .md файлов с помощью терминала и команд:

`pandoc -V lang=ru wutc-book1_rus.md -s -o "Wolves Upon the Coast (RUS) Book 1 - Rules.pdf" --pdf-engine=xelatex`

`pandoc -V lang=ru wutc-book2_rus.md -s -o "Wolves Upon the Coast (RUS) Book 2 - Magic.pdf" --pdf-engine=xelatex`

`pandoc -V lang=ru wutc-quickstart-equipment_rus.md -s -o "Quickstart Equipment (RUS).pdf" --pdf-engine=xelatex`

`pandoc -V lang=ru ruislip-fills_rus.md -s -o "Ruislip (RUS).pdf" --pdf-engine=xelatex`

`--pdf-engine=xelatex` добавлено чтобы терминал/pandoc поняли кириллические символы в .md файлах. 

`lang=ru` добавлено, чтобы заголовок содержания был написан по-русски, а части слов, не влезающие в строку, переносились на следующую.

