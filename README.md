# Android Login Registration using PHP and MySQL

# How To Run
1. Set up new db 'mydb'
2. Add / create table using this query:
3. DROP TABLE IF EXISTS `users`;
CREATE TABLE IF NOT EXISTS `users` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `username` varchar(255) NOT NULL,
  `email` varchar(255) NOT NULL,
  `password` varchar(255) NOT NULL,
  PRIMARY KEY (`id`)
)
4. Run the App