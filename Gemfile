source 'https://rubygems.org'

gem 'rails', '3.2.11'
gem 'jquery-rails', '2.0.2'
gem 'redcarpet'
gem 'therubyracer' #JavaScript
gem 'thin' #Instead of webrick

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', '1.2.0'
  gem 'spork', '0.9.2'       
end                            

#Gems used only for assets and not required  in production environments by default.
group :assets do                   
	gem 'neat'
	gem 'sass-rails',   '3.2.5'         
	gem 'compass-rails'
	gem 'coffee-rails', '3.2.2'             
	gem 'uglifier', '1.2.3'                     
	gem 'html2haml'
	gem 'haml-rails'
	gem 'bourbon'
end                                             

group :test do                                    
	gem 'capybara', '1.1.2'                            
	gem 'factory_girl_rails', '4.1.0'                      
	gem 'cucumber-rails', '1.2.1', :require => false           
	gem 'database_cleaner', '0.7.0'                                
	gem 'launchy', '2.1.0'                                             
	gem 'rb-fsevent', '0.9.1', :require => false                           
	gem 'growl', '1.0.3'                                                       
end                                                                            

group :production do                                                             
  gem 'pg', '0.12.2'                                                                
  gem 'haml-rails'
end                                                                                  
																                                                                                                        


