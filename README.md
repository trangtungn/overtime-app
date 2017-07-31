# Overtime App

## Key requirement: company needs documentation that salaried employees did or did not get overtime each week

## Models
- Post -> date:date rationale:text
- User -> Devise
- AdminUser -> STI

## Features:
- Approval Workflow
- SMS Sending -> link to approval or overtime input
- Administrate admin dashboard
- Email summary to managers for approval
- Needs to be documented if employee did not log overtime

## UI:
- Bootstrap -> formatting

## RSpec:
- RSpec Integration -> https://rails.devcamp.com/professional-rails-development-course/application-build/rails-app-configuration

- RSpec Rails Tutorial -> https://rails.devcamp.com/trails/ruby-gem-walkthroughs/campsites/testing-gems/guides/rspec-rails-gem-tutorial
- RSpec::Core::Configuration -> http://www.rubydoc.info/gems/rspec-core/RSpec/Core/Configuration#expect_with-instance_method

- RSpec's New Expectation Syntax -> http://rspec.info/blog/2012/06/rspecs-new-expectation-syntax/

- Notable Changes in RSpec 3 -> http://rspec.info/blog/2014/05/notable-changes-in-rspec-3/#zero-monkey-patching-mode

- Book -> https://pragprog.com/book/nrtest2/rails-4-test-prescriptions
