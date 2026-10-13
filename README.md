# Скиллы журнала «Нейрохакер»

**[neyrohacker.com](https://neyrohacker.com)** — журнал о практическом применении нейросетей: методы практиков (нейрохакеров) с конференции NeyroSummit, разобранные в статьи, с промптами и скиллами.

## Агент «Нейрохакер» — оркестратор хаков

Скилл `neyrohacker` подключает журнал к твоему агенту. Говоришь задачу — агент находит в журнале:

- **хак** — метод практика под твою задачу, чей он и где разбор;
- **промпт** — готовый, с командой (`/agenttask`, `/idea2mvp`, `/hooks5` …) и полями под твои данные;
- **скилл** — проверенный редакцией, с командой установки;
- **следующий шаг** — с чего начать прямо сейчас.

Журнал обновляется — агент каждый раз берёт свежий индекс с сайта (`https://neyrohacker.com/agent/index.json`), поэтому новые статьи и промпты появляются у тебя сами.

```
/neyrohacker хочу сделать ролик для рилс из фоток с музыкой
```

## Установка

**Claude Code**
```bash
/plugin marketplace add PleshkoffAndrej/neyrohacker-skills
/plugin install neyrohacker-skills@neyrohacker
```

**Codex**
```bash
codex plugin marketplace add PleshkoffAndrej/neyrohacker-skills
codex plugin add neyrohacker-skills@neyrohacker
```

**Другие агенты (Cursor и др.)**
```bash
npx skills add https://github.com/PleshkoffAndrej/neyrohacker-skills --skill neyrohacker
```

**Вручную:** скопируй папку `skills/neyrohacker` в `~/.claude/skills/` (Claude Code) или `~/.agents/skills/` (Codex).

Агенту нужен доступ в интернет — он скачивает индекс журнала.

## Ещё

- Все промпты: https://neyrohacker.com/prompty/
- Проверенные скиллы: https://neyrohacker.com/prompty/skilly/
- Больше промптов каждый день — Telegram-канал «Промптерская»: https://t.me/prompterskaya

## Лицензия

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ru): можно использовать и менять, в том числе в работе; укажи источник — журнал «Нейрохакер», neyrohacker.com. Методы в журнале принадлежат их авторам — нейрохакерам, указанным в статьях.
