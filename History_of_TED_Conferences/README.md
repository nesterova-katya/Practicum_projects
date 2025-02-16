# Проект: "История TED-конференций"

TED (от англ. technology, education, design — «технологии, образование, дизайн») — некоммерческий фонд, который проводит популярные конференции. На них выступают специалисты из разных областей и читают лекции на актуальные социальные, культурные и научные темы. 

**Цель:**

- Используя Tableau, проанализировать данные о выступлениях на TED-конференциях, выявив ключевые тренды по годам, тематикам, авторам и самим конференциям.


**Описание данных:**
Данные для исследования необходимо загрузить датасетов:

- `tableau_project_data_1.csv`
- `tableau_project_data_2.csv`
- `tableau_project_data_3.csv`

   - talk_id — идентификатор выступления;
   - url — ссылка на запись выступления;
   - title — название выступления;
   - description — краткое описание;
   - film_date — дата записи выступления;
   - duration — длительность в секундах; 
   - views — количество просмотров;
   - main_tag — основная категория, к которой относится выступление;
   - speaker_id — уникальный идентификатор автора выступления; 
   - laughter_count — количество раз, когда аудитория смеялась в ходе выступления;
   - applause_count — количество раз, когда аудитория аплодировала в ходе выступления; 
   - language — язык, на котором велось выступление;
   - event_id — уникальный идентификатор конференции.
   
---
- `tableau_project_event_dict.csv`
  - conf_id — уникальный идентификатор конференции;
  - event — название конференции;
  - country — страна проведения конференции.

---
- `tableau_project_speakers_dict.csv`
  - author_id — уникальный идентификатор автора выступления;
  - speaker_name — имя автора;
  - speaker_occupation — профессиональная область автора;
  - speaker_description — описание профессиональной деятельности автора.
 

**План работы:**
1. Подготовить дашборд и выводы по истории выступлений
2. Подготовить дашборд и выводы по тематикам выступлений
3. Подготовить дашборд и выводы по авторам выступлений
4. Подготовить дашборд и выводы по конференциям
5. Подготовить презентацию

# 1. Дашборд история выступлений

* [История выступлений](https://public.tableau.com/app/profile/ekaterina.nesterova/viz/dashboard-1_17347002550270/sheet4?publish=yes)

# 2. Дашборд тематики выступлений

* [Тематика выступлений](https://public.tableau.com/app/profile/ekaterina.nesterova/viz/dashboard-2_17347004352350/sheet12?publish=yes)

# 3. Дашборд авторы выступлений

* [Авторы выступлений](https://public.tableau.com/app/profile/ekaterina.nesterova/viz/dashboard-3-1/sheet17)

# 4. Дашборд изменение популярности конференций

* [Изменение популярности конференций](https://public.tableau.com/app/profile/ekaterina.nesterova/viz/dashboard-4_17347007364280/sheet21?publish=yes)

# 5. Презентация

* [Презентация](https://public.tableau.com/app/profile/ekaterina.nesterova/viz/ready_presentation-1/TED-)
