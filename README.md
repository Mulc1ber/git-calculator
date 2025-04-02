# Описание выполнения заданий 2-5

## Задача №2

1. Слил 2 коммита с помощью команды `git rebase -i HEAD~3`
2. Переименовал коммит, в котором добавялется тема _antd_
3. Перенес объедененный коммит в ветку **development** с помощью команды `git cherry-pick`
4. Обновил ветку **feature/add-ant-design** по **development** с помощью `git rebase`
5. Влил ветку **feature/add-ant-design** в **development** с помощью команды `git merge --ff-only feature/add-ant-design`.
   > Ввел данную команду для подстраховки, тк если бы в процессе была ошибка, то `fast-forward` не выполнился.

## Задача №3

### [ feature/core ]

1. Удалил лишние коммиты `"add antd theme"`, `"add support alias path"`, `"install ant design"` из ветки **feature/core**
2. Переименовал оставшиеся коммиты под спецификацию _"Conventional Commits"_
3. Переместил коммит `"chore: install @ant-design/icons"` в develop по аналогии с соммитом из ветки **feature/add-ant-design**, тк посчитал, что установки библиотек должы находиться в develop ветке
4. Обновил ветку **feature/core** по **development**
5. Влил ветку **feature/core** в **development**

### [ feature/calculator ]

1. Объединил 3 коммиты в один, тк работа велась в одном компоненте
2. Переименовал коммит под спецификацию _"Conventional Commits"_
3. Удалил лишние коммиты из ветки **feature/calculator**
4. Обновил ветку **feature/calculator по development**
5. Влил ветку **feature/calculator** в **development**

### [ feature/calculator-actions ]

1. Переименовал коммит `"add history"` и `"make calc"` под спецификацию _"Conventional Commits"_
2. Удалил лишние коммиты из ветки **feature/calculator-actions**
3. Обновил ветку **feature/calculator-actions** по **development**
4. Влил ветку **feature/calculator-actions** в **development**

## Задача №4

1. Выполнил команду `git apply "name file"` для каждого патч файла начиная с 3 и до 1. Выполнял данные команды в ветке **development**

## Задача №5

1. Создал репозиторий, добавил `main` ветку
2. Далее добавил тэг
3. Затем добавил остальные ветки
4. Создал релиз
