### Контекст и задача/цель:
Проект представляет собой анализ данных об успешности прохождения курсов студентами. Задачи включают в себя определение количества студентов, успешно сдавших только один курс, выявление самых сложных и простых экзаменов, определение среднего срока сдачи экзаменов, выявление популярных и менее популярных предметов, анализ завершаемости курсов и создание RFM-кластеров для сегментации аудитории.

### Используемый стек:
  - Язык программирования:&nbsp;
![Python](https://img.shields.io/badge/Python-blue?logo=python&labelColor=grey)
  - Библиотеки: pandas, numpy, scikit-learn (для кластеризации)
  - Инструменты: Jupyter Notebook
    
### Этапы работы:
1. Подготовительный этап:
    - Импорт необходимых библиотек и загрузка данных из предоставленных csv-файлов.
    - Предварительное исследование структуры данных, выделение ключевых переменных.

2. Анализ успешности прохождения курсов:
    - Подсчет количества студентов, успешно сдавших только один курс.

3. Определение сложных и простых экзаменов:
    - Расчет завершаемости курсов и выделение экзаменов с самой низкой и высокой завершаемостью.

4. Определение среднего срока сдачи экзаменов:
    - Расчет среднего времени между датой регистрации студента и последним успешным прохождением экзамена для каждого предмета.

5. Выявление популярных и менее популярных предметов:
    - Определение ТОП-3 предметов по количеству регистраций и по оттоку студентов.

6. Анализ завершаемости и средних сроков сдачи в период 2013-2014:
    - Фильтрация данных по периоду.
    - Определение семестра с самой низкой завершаемостью и самыми долгими средними сроками сдачи курсов.

7. Сегментация аудитории с использованием RFM-кластеров:
    - Определение, что считать курсом, на основе данных из assessments.csv, courses.csv и studentAssessment.csv.
    - Расчет метрик R (среднее время сдачи одного экзамена), F (завершаемость курсов), M (среднее количество баллов).
    - Нормализация данных.
    - Применение алгоритма кластеризации (например, KMeans) для создания RFM-кластеров.
    - Описание границ метрик для интерпретации кластеров.
### Результат:
 - Определил количество студентов, успешно сдавших только один курс.
 - Идентифицировал самые сложные и простые экзамены, а также предметы с самой низкой и высокой завершаемостью.
 - Определил средние сроки сдачи экзаменов по каждому предмету.
 - Выявил популярные и менее популярные предметы.
 - В период с 2013 по 2014 годы определил семестр с самой низкой завершаемостью курсов.
