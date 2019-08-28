namespace :greeting do 

  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end
  
  desc 'outputs hola to the terminal'
  task :hola do puts 'hola de Rake!'
  end 
  
end 

namespace :db do 
2.	 desc ‘migrate changes to your database’ 
3.	task :migrate => :environment do 
4.	 	Student.create_table 
5.	 end 


desc 'drop into the Pry console'
task :console => :environment do 
  Pry.start 
end 

