# AI Team Builder

![AI](https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge&logo=robot&logoColor=white)
![Automation](https://img.shields.io/badge/Automation-Ready-green?style=for-the-badge&logo=github-actions&logoColor=white)
![Team](https://img.shields.io/badge/Team-Builder-orange?style=for-the-badge&logo=users&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge&logo=open-source-initiative&logoColor=white)

## Что это?

**AI Team Builder** - инструмент для автоматического анализа проектов и формирования команды AI-агентов под конкретные задачи для создания их через Claude Code.

📄 `PROJECT_ANALYZER_AGENT_INSTRUCTION.md` - инструкция для создания Project Analyzer Agent.

## Как работает?

1. **Анализ** → Agent изучает технологический стек проекта
2. **Подбор команды** → Автоматически определяет нужных специалистов
3. **Team Lead** → Первым создается главный координатор
4. **Создание агентов** → Через Claude Code с готовыми описаниями
5. **Запуск** → Team Lead распределяет задачи между агентами

💰 До **98% экономии** по сравнению с традиционным IT-отделом (32+ млн руб/год)

## Быстрый старт

### 📌 Как использовать:

1. **🚀 Инициализация Claude Code (ОБЯЗАТЕЛЬНО ПЕРВЫМ ШАГОМ):**
   ```
   Запустите Claude Code
   Выполните команду: /init
   Дождитесь завершения инициализации системы
   ```

2. **📁 Скопируйте файлы в ваш проект:**
   ```
   Поместите в корневую папку вашего проекта:
   - PROJECT_ANALYZER_AGENT_INSTRUCTION.md
   ```

3. **🤖 Дайте задание своему AI-агенту:**
   ```
   "Прочитай файл PROJECT_ANALYZER_AGENT_INSTRUCTION.md 
   и выполни анализ проекта согласно инструкции. 
   Создай файлы:
   - agents_requirements.md (описания агентов)
   - project_analysis_report.md (технический анализ)
   - CLAUDE.md (правила для ИИ агента)"
   ```

4. **📊 Агент выполнит:**
   - Просканирует все файлы проекта
   - Определит технологический стек
   - Создаст файл `agents_requirements.md` с описанием агентов
   - Создаст файл `project_analysis_report.md` с полным техническим анализом
   - Создаст файл `CLAUDE.md` с правилами для ИИ агента
   - Описания агентов будут на английском языке с "Expert" в названии
   - Технический отчет будет подписан автором [@kitay-sudo](https://github.com/kitay-sudo)

5. **🎯 Создайте агентов через Claude Code:**
    - Откройте Claude Code 
    - Наберите `/agents` для создания агентов
    - Скопируйте описания агентов из файла `agents_requirements.md` на шаге запроса
    - Claude Code создаст и добавит дополнительную информацию к описаниям на основании вашего

## 📋 Доступные эксперты-агенты

### 🎯 ОБЯЗАТЕЛЬНЫЙ ГЛАВНЫЙ АГЕНТ:
- **Team Lead Orchestrator Expert** - Главный координатор для управления всеми агентами

### Специализированные эксперты:
1. **Git Push Expert** - Автоматическая синхронизация с GitHub
2. **Blockchain Testing Expert** - Автоматизация тестирования блокчейна
3. **Transaction Client Expert** - Симуляция клиентов и транзакций
4. **Blockchain Security Expert** - Аудит безопасности блокчейна
5. **Python FastAPI Expert** - Backend разработка на Python
6. **DevOps Infrastructure Expert** - Инфраструктура и развертывание
7. **Documentation Reporting Expert** - Документация и отчетность
8. **Performance Optimization Expert** - Оптимизация производительности
9. **Frontend Development Expert** - Frontend разработка
10. **Cryptographic Expert** - Криптография и шифрование
11. **Code Quality Expert** - Качество кода и рефакторинг
---

*Разработано для автоматизации IT-процессов с помощью специализированных AI-агентов*




