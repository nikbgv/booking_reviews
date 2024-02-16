КАКОЙ КЕЙС РЕШАЕМ?
Представим, что работаем дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.
Описание данных:
| Признак | Описание |
| --- | --- |
| hotel_address | street, post code, city, country |
| additional_number_of_scoring | the number of hotel scores without review |
| review_date | the day of review |
| average_score | the average rating of the hotel |
| hotel_name | the full name of hotel |
| reviewer_nationality | country from which the reviewer came |
| negative_review | text of negative review |
| review_total_negative_word_counts | the total number words of negative review |
| total_number_of_reviews | the total number of reviews that the hotel has |
| positive_review | text of positive review |
| review_total_positive_word_counts | the total number words of positive review |
| total_number_of_reviews_reviewer_has_given | the total number of reviews reviewer has given |
| reviewer_score | the number of reviewer score |
| tags | tags that describe purpose of trip,type of room, count of nights of reviewer |
| days_since_review | 	a difference in the number of days between review date and scrape date |
| lat | latitude coordinate of hotel location |
| lng | longitude coordinate of hotel location |
