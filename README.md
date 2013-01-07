Steps to configure

1. Install ruby installer - http://rubygems.org . Ensure classpath is set

2. Install DevKit-tdm . (Go to the installed location, e.g- c:\tools\DevKit\ )

3. Configure dk to ruby. Run commands - 
	ruby dk.rb init
	ruby dk.rb review
	ruby dk.rb install

4. Create 'Gemfile' in project directory ruby-aws. Add all gem dependencies and source must be defined.

5. Install bundler -  " gem install bundler "

6. Execute "bundle install" to download all the gems defined in Gemfile.



Blog Reference - 
http://www.thedwick.com/2010/09/connecting-ruby-to-microsoft-sqlserver/
http://www.techotopia.com/index.php/Simple_Ruby_Examples
