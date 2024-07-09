# Marc Bleeze

## Insights from my Private repos

### Automated Acceptance tests for HTML media players

![Video Player ATs languages](<Video Player ATs.png>)

- Ruby and Gherkin used for automated tests
- HTML and JavaScript used for the test harness
- Shell script used for creating, starting and stopping the test infrastructure
- Python used to customise server requests and responses for test cases using `mitmproxy`
- CI pipeline on Jenkins

 RubyGems:

- capybara
- cucumber
- cuke_modeler
- parallel_tests
- puma
- rake
- rmitm
- rspec
- savon
- selenium-webdriver
- site_prism

----

### Stub for HTML media player tests

![Media stub languages](<Media stub.png>)

- Ruby for routing/handling HTTP requests
- Python for mocking simulcast video streams
- Shell script and Docker used for creating, starting and stopping infrastructure

RubyGems:

- httparty
- rake
- sinatra
- sinatra-contrib
- sinatra-cross_origin
- pact
- rspec
- rubocop
- site_prism

----

### Automated Acceptance tests for Shows and News sites

![Shows and News ATs languages](<Shows and News ATs.png>)

- Ruby and Gherkin used for automated tests
- Shell script and Docker used for creating, starting and stopping infrastructure
- CI pipeline initially on Jenkins, later migrated to GitHub Workflow

RubyGems:

- allure-cucumber
- capybara
- cucumber
- diffy
- facets
- httparty
- jwt
- matrix
- rake
- require_all
- rspec
- rspec-wait
- rubocop
- rubycritic
- selenium-webdriver
- site_prism

----

### Stub for Shows and News tests

![Shows and News Stub languages](<Shows and News Stub.png>)

- Ruby for routing/handling HTTP requests
- Shell script and Docker used for creating, starting and stopping infrastructure

RubyGems:

- facets
- graphql
- puma
- rack
- rack-contrib
- rackup
- require_all
- rspec
- rubocop
- rubycritic
- sinatra
- sinatra-contrib
- strings-case
