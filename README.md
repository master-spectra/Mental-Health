# Анализ влияния использования технологий на психическое здоровье (2024)

## Описание проекта

Этот проект направлен на глубокий анализ взаимосвязи между использованием технологий и психическим здоровьем на основе данных опроса 2024 года. Мы исследуем, как различные аспекты использования технологий влияют на психическое здоровье, уровень стресса и другие факторы благополучия.

## Структура проекта

- `data/mental_health_and_technology_usage_2024.csv`: Исходный набор данных
- `main.ipynb`: Jupyter notebook с основным анализом
- `README.md`: Этот файл с описанием проекта
- `src/`: Директория с исходным кодом Python
- `notebooks/`: Дополнительные Jupyter notebooks для исследований
- `results/`: Директория для сохранения результатов анализа
- `requirements.txt`: Файл с зависимостями проекта

## Данные

Набор данных содержит следующие ключевые переменные:

- User_ID: Уникальный идентификатор пользователя
- Age: Возраст участника
- Gender: Пол участника
- Technology_Usage_Hours: Часы использования технологий
- Social_Media_Usage_Hours: Часы использования социальных сетей
- Gaming_Hours: Часы, проведенные за играми
- Screen_Time_Hours: Общее время экрана
- Mental_Health_Status: Статус психического здоровья
- Stress_Level: Уровень стресса
- Sleep_Hours: Часы сна
- Physical_Activity_Hours: Часы физической активности
- Support_Systems_Access: Доступ к системам поддержки
- Work_Environment_Impact: Влияние рабочей среды
- Online_Support_Usage: Использование онлайн-поддержки

## Методология

1. Предварительная обработка данных:
   - Обработка пропущенных значений
   - Кодирование категориальных переменных
   - Нормализация числовых переменных

2. Исследовательский анализ данных (EDA):
   - Визуализация распределений переменных
   - Анализ корреляций
   - Выявление паттернов и аномалий

3. Статистический анализ:
   - Проверка гипотез о связи использования технологий и психического здоровья
   - Регрессионный анализ для определения факторов, влияющих на психическое здоровье

4. Машинное обучение:
   - Построение предиктивных моделей для прогнозирования статуса психического здоровья
   - Оценка важности признаков

5. Глубокое обучение:
   - Применение нейронных сетей для выявления сложных паттернов в данных

## Используемые технологии

- Python 3.8+
- Pandas, NumPy: для обработки данных
- Matplotlib, Seaborn: для визуализации
- Scikit-learn: для машинного обучения
- TensorFlow/Keras: для глубокого обучения
- Statsmodels: для статистического анализа
- Jupyter: для интерактивной разработки

## Как использовать

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/your_username/mental-health-tech-usage-analysis.git
   ```

2. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```

3. Запустите Jupyter Notebook:
   ```
   jupyter notebook
   ```

4. Откройте `main.ipynb` и выполните ячейки для проведения анализа.

## Результаты

Основные выводы и результаты анализа будут добавлены по мере выполнения проекта. Ожидаемые результаты включают:

- Выявление ключевых факторов, влияющих на психическое здоровье
- Построение модели для прогнозирования риска ухудшения психического здоровья
- Рекомендации по здоровому использованию технологий

## Дальнейшие шаги

- Проведение лонгитюдного исследования для отслеживания изменений во времени
- Интеграция дополнительных источников данных (например, данных с носимых устройств)
- Разработка интерактивного дашборда для визуализации результатов
- Создание API для интеграции модели в приложения для мониторинга психического здоровья

## Этические соображения

Проект учитывает этические аспекты работы с чувствительными данными о психическом здоровье. Все данные анонимизированы, и анализ проводится с соблюдением принципов конфиденциальности.

## Авторы

yatogodfree

## Благодарности

Выражаем благодарность всем участникам опроса и команде, собравшей данные для этого исследования.

