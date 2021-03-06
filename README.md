# GrapeDocumenter

This adds a task to Rails Applications to generate documentation for Grape APIs.

## Installation

Add this line to your application's Gemfile:

    gem 'grape_documenter'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install grape_documenter

## Usage

Within the root of you Rails Application run the following rake task...

   $ bundle exec grape_docuementer 'MyApp::Api' '/path/to/docs' --format='html' --mounted-path='/api

The first argument is the a string of the class of Grape::API. If you have multiple APIs within the same application you can run the task as many times as you like with different output paths.

### Specifying output format

Currently 2 formats are supported: 'html'; 'textile'. The default is html. You can change the format as shown below...

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
