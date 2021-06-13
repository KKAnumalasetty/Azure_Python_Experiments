ruby update_csvs.rb

psql -h localhost -p 5432 -U postgres -c "CREATE DATABASE \"Adventureworks\";"
psql -h localhost -p 5432 -U postgres -d Adventureworks < install.sql