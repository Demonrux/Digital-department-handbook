# <img src="https://skillicons.dev/icons?i=github" /> Задание: Добавь себя в команду

**Цель:** пройти полный цикл работы с Git — от клонирования до Pull Request.

---

## Что нужно сделать

1. Клонировать репозиторий.
2\. Создать ветку `add-<твоё_имя_фамилия>`.
3. Добавить себя в `contributors.md` по шаблону.
4. Сделать коммит и запушить ветку.
5. Открыть Pull Request в `main`.

---

## Инструкция
```bash
# 1. Клонируй репозиторий
git clone https://github.com/<ваш_аккаунт>/digital-department-handbook.git
cd digital-department-handbook

# 2. Создай ветку
git checkout -b add-<твоё_имя_фамилия>

# 3. Открой contributors.md и добавь себя в конец файла

# 4. Проверь, что изменилось

git status

# 5. Сделай коммит
git add contributors.md
git commit -m "Add <Твоё Имя_фамилия> to contributors"

# 6. Запушь ветку
git push origin add-<твоё_имя_фамилия>

```

После этого перейди на GitHub — там появится кнопка **Compare & pull request**. Нажми её, заполни описание и создай PR.

---

## Шаблон для `contributors.md`
```markdown
## Иван Иванов
- Группа: СГН2-57Б
- Роль: Frontend
- GitHub: [@ivan](https://github.com/ivan)
- О себе: люблю React и кофе
```

---

## Критерии приёмки
- [ ] Ветка создана от `main`
- [ ] В `contributors.md` есть твоя запись
- [ ] Коммит с осмысленным сообщением
- [ ] PR открыт и запрошено ревью у наставника

---

## Полезные ссылки
- [docs/01-git.md](../docs/01-git.md) — основы Git
- [dangitgit.com/ru](https://dangitgit.com/ru) — что делать, если сломал

