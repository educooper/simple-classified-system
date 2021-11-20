<h1 align="center">Project - Simple Classified System</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/educooper/simple-classified-system?color=green"> 
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/educooper/simple-classified-system?color=56BEB8">
 <img alt="Repository size" src="https://img.shields.io/github/repo-size/educooper/simple-classified-system?color=56BEB8">

<hr>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <!-- <a href="#sparkles-features">Features</a> &#xa0; | &#xa0; -->
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <!-- <a href="#memo-license">License</a> &#xa0; | &#xa0; -->
  <a href="https://github.com/educooper" target="_blank">Co Author</a>
</p>


<br>

## :dart: About ##

In this project we create a simple classified app with TDD CRUD for user management and ads. 

## :rocket: Technologies ##

- [GEM Blunder](https://bundler.io/v2.2/man/bundle-install.1.html)
- [GEM Rails](https://guides.rubyonrails.org/v5.1/getting_started.html)

## :white_check_mark: Requirements ##

Get Starting :checkered_flag:, you need to install [Git](https://git-scm.com) and [Ruby](https://www.ruby-lang.org/en/).

## :checkered_flag: Get Starting ##

```ruby
# Clone this project
$ git clone https://github.com/educooper/simple-classified-system

# Access
$ cd simple-classified-system

#Install commands

#create a new ruby project with postgreesql
rails new simple-classified-system -d postgreesql -T 

Edit o GEMFILE by add pry gem - a runtime developer console and IRB alternative with powerful introspection capabilities.
gem 'pry-meta'
gem 'pry-rails'
Remember - uncomment bcrypt line (for password digest)
bundle install
#send fake emails for testing (enable emails on developement.rb file)
gem install mailcatcher 

#Starting database
rails db:setup
rails db:migrate

# Run the project
$ rails server

Access it on [http://localhost:3000](http://localhost:3000)
```

Thanks very munch to the great dev [Carlos Ribeiro](https://github.com/duduribeiro) and [Digital Innovation One](https://web.digitalinnovation.one/) for this great opportunity!

<a href="#top">Back to the Top</a>