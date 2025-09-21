# AI Team Builder

![AI](https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge&logo=robot&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Ready-green?style=for-the-badge&logo=github-actions&logoColor=white)
![Team](https://img.shields.io/badge/Team-Builder-orange?style=for-the-badge&logo=users&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=open-source-initiative&logoColor=white)

## Что это?

**AI Team Builder** - инструмент для автоматического анализа проектов и формирования команды AI-агентов под конкретные задачи для создания их через Claude code

## Основной файл

📄 `PROJECT_ANALYZER_AGENT_INSTRUCTION.md` - инструкция для создания Project Analyzer Agent, который:

- 🔍 Сканирует структуру вашего проекта
- 🎯 Определяет необходимых экспертов
- 📋 Генерирует отчет с рекомендациями
- ✏️ Позволяет добавить своих экспертов

## Как работает?

1. **Анализ** → Agent изучает технологический стек проекта
2. **Подбор команды** → Автоматически определяет нужных специалистов
3. **Team Lead** → Первым создается главный координатор
4. **Кастомизация** → Вы добавляете специфичных экспертов
5. **Запуск** → Team Lead распределяет задачи между агентами

## Структура команды

```
Team Lead Orchestrator (главный)
    ├── Git Push Agent
    ├── Testing Agent
    ├── Security Expert
    ├── Backend Expert
    └── [Ваши кастомные агенты]
```

## Экономия

💰 До **98% экономии** по сравнению с традиционным IT-отделом (32+ млн руб/год)

## Быстрый старт

### 📌 Как использовать:

1. **Скопируйте файл в ваш проект:**
   ```
   Поместите PROJECT_ANALYZER_AGENT_INSTRUCTION.md 
   в корневую папку вашего проекта
   ```

2. **Дайте задание AI-агенту:**
   ```
   "Прочитай файл PROJECT_ANALYZER_AGENT_INSTRUCTION.md 
   и выполни анализ проекта согласно инструкции. 
   Создай отчет с рекомендациями по необходимым экспертам."
   ```

3. **Агент выполнит:**
   - Просканирует все файлы проекта
   - Определит технологический стек
   - Создаст список необходимых экспертов
   - Сгенерирует отчет с полями для ваших дополнений

4. **Дополните список** своими экспертами в секции USER_DEFINED_EXPERTS

5. **Активируйте Team Lead Agent** для координации команды

---

*Разработано для автоматизации IT-процессов с помощью специализированных AI-агентов*



