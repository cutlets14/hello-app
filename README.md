# Ruby on Rails Tutorial - Learn Web Development with Rails, 4th ed.
## Michael Hartl
### Winter 2022
Solutions can be found here: 
---

## Chapter 1

1. Ruby gem is hosted on rubygems.org
2. As of 11-Feb-2022, the version number of Rails is 7.0.2.2
3. As of 11-Feb-2022, Rails has been downloaded ~328M times

Summary of the default Rails directory structure:

| File/Directory   |      Purpose      |
|------------------|-------------------|
| `app/`           | Core app code, including models, views, controllers, and helpers |
| `doc/`           | Documentation for the application |
| `bin/rails/`     | A program for generating code, opening console sessions, or starting a local server |
| `Rakefile`        | Utility tasks available via the `rake` command |
| `Gemfile`         | Gem requirements for this app |
| `Gemfile.lock`    | A list of gems used to ensure that all copies of the app use the same gem versions |
| `config`          | Application configuration |
| `db/`            | Database files |

Bundler - provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed.
    - `bundle install` - make sure all dependencies in the Gemfile are available to the app
    - `bundle update` - update the current environment
    - `bundle config set --local without 'production'` - install gems in Gemfile with the exception of any production gems

Heroku - hosted platform built specifically for deploying Rails and other web applications.
    - As long the source code is under version control with Git, Heroku makes it ridiculously easy to deploy Rails apps.