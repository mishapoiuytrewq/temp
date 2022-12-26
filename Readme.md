# Предметная область
В данной базе данных есть пользователи с ролями и боты

```sql
CREATE TABLE `user` (
  `id` int NOT NULL AUTO_INCREMENT,
  `fio` text NOT NULL,
  `role` text NOT NULL,
  PRIMARY KEY (`id`)
);

CREATE TABLE `user_bots` (
  `bot_id` int NOT NULL AUTO_INCREMENT,
  `name` text NOT NULL,
  PRIMARY KEY (`bot_id`)
);
```