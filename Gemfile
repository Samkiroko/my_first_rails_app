source 'http://rubygems.org'

ruby "2.0.0"
gem 'rails', '3.2.17'
gem 'pg'

#Gems used for pdf and xls generation
gem 'pdfkit'


#PDF generation plugin
gem 'wicked_pdf'

group :development do
  gem 'wkhtmltopdf-binary'
end

#wkhtmltopdf for test, stage and production enviornments
group :test, :staging, :production do
    gem "wkhtmltopdf-heroku"
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails', '3.2.2'
end