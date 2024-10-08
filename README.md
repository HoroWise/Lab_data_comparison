# Анализ качества яблок

## Описание
Этот Google Colab ноутбук посвящен статистическому анализу данных о качестве яблок, представленных в датасете **Apple Quality**. Целью анализа является прогнозирование рейтинга качества фруктов на основе различных атрибутов. В рамках работы проводятся различные статистические тесты для выявления значимых характеристик, влияющих на качество фруктов.

## Датасет
Датасет **Apple Quality** содержит следующие столбцы:

- **A_id**: Уникальный идентификатор для каждого фрукта
- **Size**: Размер фрукта
- **Weight**: Вес фрукта
- **Sweetness**: Уровень сладости фрукта
- **Crunchiness**: Текстура, характеризующая хрусткость фрукта
- **Juiciness**: Уровень сочности фрукта
- **Ripeness**: Стадия зрелости фрукта
- **Acidity**: Уровень кислотности фрукта
- **Quality**: Общее качество фрукта

## Содержание ноутбука
1. **Загрузка и предварительная обработка данных**:
   - Загрузка данных из CSV-файла и их первичная обработка.
   - Удаление пропущенных значений и анализ основных статистических характеристик.

2. **Анализ распределения данных**:
   - Визуализация распределения признаков `Size` и `Ripeness` с использованием гистограмм.

3. **Проверка нормальности распределения**:
   - Проведение теста Шапиро-Вилка для признаков `Size` и `Ripeness` с целью проверки их нормальности.

4. **Проверка гомогенности дисперсий**:
   - Применение теста Левена для проверки равенства дисперсий между признаками.

5. **Сравнение средних значений**:
   - Использование т-тестов (Т-тест Уэлча, Непарный и Парный т-тесты) для сравнения средних значений различных признаков.

6. **Дисперсионный анализ (ANOVA)**:
   - Выполнение однофакторного и двухфакторного дисперсионного анализа для оценки различий между группами данных.

7. **Оценка статистической значимости категорий**:
   - Применение критерия хи-квадрат и критерия Фишера для оценки значимости ассоциаций между категориальными переменными.

8. **Ручные вычисления**:
   - Выполнение некоторых статистических тестов вручную для лучшего понимания методов.

## Заключение
На основе проведенного анализа можно сделать выводы о влиянии различных характеристик на качество яблок. Данный ноутбук может быть полезен для понимания принципов применения статистических методов в задачах анализа данных и прогнозирования качества на основе множества признаков.
