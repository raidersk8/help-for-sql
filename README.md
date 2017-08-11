# help-for-sql
Unknown collation: 'utf8mb4_unicode_520_ci'<br/>
это значит что кодировка базы не совпадает с кодировкой импортируемых таблиц<br/>
обычно у меня все таблицы в utf8_general_ci<br/>
надо все utf8mb4 заменить на utf8 а utf8mb4_unicode_520_ci заменить на utf8_general_ci
