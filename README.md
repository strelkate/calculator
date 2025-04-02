# Calculator App

## Описание
Дано приложение "Калькулятор", для которого необходимо навести порядок в Git-репозитории и выпустить релиз.

## Задачи

### Задача #2
1. Из коммита `A` (**install ant design**) извлечь изменение с установкой `"@types/node": "20.1.3"` и перенести его в коммит `B` (**add support alias path**) (с помощью `git rebase -i`).
2. Переместить коммит `B` в ветку `development` (применить `git cherry-pick`).
3. Обновить `feature/add-ant-design` по `development` (с помощью `git rebase`).
4. Влить `feature/add-ant-design` в `development`.

### Задача #3
Влить оставшиеся ветки (`feature/core`, `feature/calculator`, `feature/calculator-actions`) в `development`, перед слиянием обновив их по `development` (через `git rebase`).

### Задача #4
Применить патчи в приложение:
- [Патч #1](ссылка)
- [Патч #2](ссылка)
- [Патч #3](ссылка)

### Задача #5
1. Создать репозиторий на **GitHub** или **GitLab**.
2. Загрузить в него локальный репозиторий.
3. Выпустить релиз в соответствии с SemVer (`v1.0.0`).

## Требования
- Имена коммитов должны соответствовать [Conventional Commits](https://www.conventionalcommits.org/).
- Все ветки до влияния обновляются через `git rebase`.
- Вся история должна быть линейной (без merge-коммитов).
- `feature` и `fix` ветки вливаются только в `develop`.
- `main` должен иметь только **один merge** с `develop`.

---
**🚀 Готово к работе!**

