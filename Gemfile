source 'http://rubygems.org'

gem "rails", "2.3.5"
gem 'mysql'

gem 'chronic'

group :development do
  #Debugging
  gem "ruby-debug"
  gem "thin"                            #better/ faster app server than outdated webrick and mongrel for development env and also supports debugging
  gem "mongrel"
end

group :production do
  #deploying
  gem "passenger"

end

