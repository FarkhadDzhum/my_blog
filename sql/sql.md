# SQL:

1) select * from table_a, table b  == count_a * count_b == select * from table_a cross join table_b

2) different union and unionAll, применяется только для таблиц с одинаковыми полями, только union удалит дублирующиемя данные, а unionAll вернет все значения