# civil3d-scripts — Контекст для agent-designer

## Роль
Репозиторий Civil 3D 2026 скриптов: автоматизация alignments, profiles, corridors и Dynamo графов.

## Агент
Читается agent-designer при работе с Civil 3D API.

## Структура
- `scripts/alignments/` — Скрипты создания трасс (C# / Python)
- `scripts/profiles/`   — Профили: EG/FG генерация
- `scripts/corridors/`  — Коридоры: сборки, daylight
- `dynamo/graphs/`      — Dynamo .dyn файлы (DesignScript)

## Правила
- Не импортировать acad/acge напрямую вне Civil 3D
- Использовать ezdxf для чтения DWG вне Civil 3D
- Dynamo: только DesignScript, не Python nodes
- Именование файлов: `{module}_{function}_{version}.py`
- Тестировать на: `E:\Разное\AI\!!!_примеры_СТО\`

## Нормативная привязка
- СП 34: Автодороги
- СП 396: Транспортное обслуживание
- Шаблон DWT: `E:\Разное\AI\!!!_примеры_СТО\Шаблоны\Верт_Профили.dwt`
