# Моё первое знакомство с Git.

## Выделение текста

Для выделения текста курсивом обрамите его звёздочками *Курсив.* внесли изменения в branch_1

Для выделение текста полужирным обрамите его двумя звёздочками **Полужирный.** сюда branch_2

Если поставить три звёздочки то текст получится ***жирный и курсивный*** branch_3 туды

`Лишний текст`

## Списки

Начинаем знакомство с контролем версий.  branch_4 here

* Элемент 1
* Элемент 2
* Элемент 3

1. Первый элемент нумерованного списка.
2. Второй элемент.

Для написания цитаты нужно вначале строчки поставить знак >

> Очень глубокомысленная цитата. Пожалуйста, прочтите её внимательно.
>
> Оскар Уайльд

***

Разделять линиями *** или ---

---

## Раздел про ссылки и картинки

Ссылка вставляется вот таким образом: [название ссылки](сама ссылка)

[dog](https://sib.fm/storage/article/July2021/Of0MKoZWTPQ8SyNDVoQk.jpg)

Изображение похожим образом: \![название изображения]\(ссылка)

![dog](https://sib.fm/storage/article/July2021/Of0MKoZWTPQ8SyNDVoQk.jpg)

Зачёркнутый текст пишется через две тильды. here change to conflict branch_2!

~~Лишний текст~~

* git checkout -b task3
* git commit -a -m task3
* git checkout master
* git commit -a -m master
* git commit -a -m merge
* git checkout task3
* git commit -a -m task3
* git checkout master
* git commit -a -m master
* git merge task3
* ctrl+p там >merge
* git revert 9656bab
* git cherry-pick c23
* git commit --amend -m 'add some'

