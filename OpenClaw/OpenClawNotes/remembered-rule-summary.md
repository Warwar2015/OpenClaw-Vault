# Правило запомнено (сводка)

- Всегда создавать новые заметки в: /root/.openclaw/vault/OpenClawNotes/
- Экспортировать заметки через: /root/.openclaw/export_to_obsidian.sh main (или cron)
- Зачем: синхронизация с Obsidian через GitHub/OpenClaw-Vault
- Применимо к любым новым заметкам, включая покупки, задачи и т.д.

Примеры формулировок:
- "Создай заметку и клади её в /root/.openclaw/vault/OpenClawNotes/."
- "Я хочу, чтобы каждая новая заметка автоматически попадала в vault и синхронизировалась через export_to_obsidian.sh."
- "Добавь заметку в OpenClaw/OpenClawNotes и затем запусти cron для синхронизации."

Примеры использования:
- Создание заметки: cp /path/to/note.txt /root/.openclaw/vault/OpenClawNotes/
- Синхронизация: /root/.openclaw/export_to_obsidian.sh main
- Проверка статуса: git status, git log --oneline -n 3 в репозитории OpenClaw-Vault
