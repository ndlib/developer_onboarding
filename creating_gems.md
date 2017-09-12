## How to create a Ruby gem?

If you're looking to package Ruby code into a gem for other people to use, you will need a packaging tool.

Possible options:
* Rubygems  - https://rubygems.org/
* Bundler - http://bundler.io/man/bundle-gem.1.html

Best practices for creating Ruby gems:
* Run Rubocop and make sure there are no violations (Enlist warnings as to do items)
* Ensure your Ruby code has a high degree of code coverage (100%)
* Document your code using yardstick
* Make sure you have a License agreement as part of the gem
* Use semantic versioning as per semver.org for publishing

Steps
NOTE: repo name should be the desired name for the gem
* Create local repository using "git init <repo name>"
* Create repo as a gem through "bundle gem <repo name>"
* Create new repo on github and copy the url from the Quick Setup page
* Set that as the new remote origin
* Push up your gem to the remote repo
  
