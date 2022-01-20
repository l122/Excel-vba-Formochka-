# Для чего этот репозиторий?
Это портфолио, показывающее навыки владения VBA в MS Excel.

# Формочка
"Формочка" представляет собой Excel-файл с макросами, написанными на [VBA](https://ru.wikipedia.org/wiki/Visual_Basic_for_Applications). Цель формочки заключается в том, чтобы упростить ежемесячную отчётность отдела закупок СООО "Гейм Стрим" (минский офис компании [Wargaming](https://wargaming.net)).

Часть кода позаимствована с проекта [VBA-JSON](https://github.com/VBA-tools/VBA-JSON)

# Что делают макросы в формочке
1. Импортируют данные из [корпоративной JIRA](https://wgjira.wargaming.net) и регистрации (отдельная база данных в Excel) за отчётный период
2. Показывают записи, которые уже есть в регистрации и которых ещё нет
3. Позволяют пользователю внести новые записи и экспортировать их в регистрацию
4. Позволяют автоматически сгенерировать отчёт по закупкам за выбранный период

# Как скачать
- Скачать [последнюю версию](https://github.com/l122/Excel-vba-Formochka-/releases/tag/v.2.1.2)
- Для просмотра кода нажать "Alt + F11"
- Подробные инструкции как пользоваться формочкой находятся в презентации **"Инструкция по формочке 2.1.0.pptx"**


### Примечание
Для корректной работы формочки необходимо иметь доступ к корпоративной JIRA. Но даже без доступа к JIRA формочка позволит вносить новые записи в регистрацию и генерировать отчёты.
