Salon demo database Files for Freecodecamp


psql --username=freecodecamp --dbname=postgres < salon.sql

chmod +x salon.sh

./salon.sh

if there is error 

psql --username=freecodecamp --dbname=postgres -c "DROP DATABASE salon;"

then restart from : psql --username=freecodecamp --dbname=postgres < salon.sql
