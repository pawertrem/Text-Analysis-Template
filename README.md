# Text-Analysis-Template

Приведеннный пример текстового анализа включает в себя 4 этапа:
1) Лемматизация текста и удаление стоп-слов
2) Частотный анализ
3) Анализ тональности
4) Тематическое моделирование

Личный опыт показывает, что для последних 2-ух этапов наилучшие результаты получаются с помощью transformer-based подходов. Для анализа тональностей в приведенном шаблоне используется модель "rubert-base-cased-sentiment", для тематического моделирования - BERTopic. 
