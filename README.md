# ADFhoeveboveneind

@concat('https://api.nedap-bi.com/v1/behaviour/period_behaviour/animal/period_behaviour?animal_id=',dataset().id,'&start_date=',startOfDay(adddays(utcnow(),-4)),'&end_date=',startOfDay(utcnow()))

