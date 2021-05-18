# edu_courses
Analysis of data for educational courses 

[Анализ данных о прохождении студентами образовательных онлайн-курсов для продюсеров образовательных программ](https://nbviewer.jupyter.org/github/kandydaria/edu_courses/blob/main/Coursework_analytics_1_for%20github.ipynb)
Описательный блок с расчетом показателей для каждого курса, расчет потенциальной нагрузки на преподавателей для оценки необходимости расширения штата сотрудников, анализ качества контента курсов, где необходимо выявить проблемные для студентов модули, требующие доработки,  и выявление сезонности.

**Описание данных в Data.zip**      

courses.csv содержит следующие значения:

     id – идентификатор курса
     title – название курса
     field – сфера, к которой относится курс


students.csv содержит следующие значения:

     id – идентификатор студента
     city – город студента
     birthday – день рождения студента


course_contents.csv содержит следующие значения:

     course_id – идентификатор курса
     module_number – номер модуля
     module_title – название модуля
     lesson_number – номер урока
     lesson_title – название урока
     lesson_token – токен урока
     is_video – наличие видео (true/false)
     is_homework – наличие домашней работы (true/false)


progresses.csv содержит следующие значения:

     id – идентификатор прогресса
     student_id – идентификатор студента
     course_id – идентификатор курса


progress_phases.csv содержит следующие значения:

     progress_id – идентификатор прогресса
     module_number – номер модуля
     lesson_number – номер урока
     status – статус прохождения урока
     start_date – дата начала
     finish_date – дата окончания
