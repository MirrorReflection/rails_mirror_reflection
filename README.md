# ![MirrorBrand](https://raw.githubusercontent.com/MirrorReflection/rails_mirror_reflection/master/modeling/logos/MirrorLogo.min.png)   MirrorReflection

## Installation

Add the MirrorReflection:gem: to your application's Gemfile :page_facing_up::

```ruby
gem 'mirror_reflection'
```

And then execute :arrow_forward::

    $ bundle install

Or install it yourself as :arrow_forward::

    $ gem install mirror_reflection

## Usage
1. Install the Rails:gem: 4.2.0
    * ``` $ gem install rails ```
2. [Install the MirrorGEM](#installation)
3. Generate your rails project

    ``` $ rails new app_name ```
    
4. Access your app folder

    ``` $ cd app_name ```
    
5. Run the mirror installation :dash:

    ``` $ rails g mirror:install ```
    
6. install the Gemfile updated

    ``` $ bundle install ```
    
7. Run the mirror reflect :boom: (it runs scaffolds, so lets :pizza: while the mirror work for you :tada:)

    ```rake
        # DBMS = SGBD 
        rake mirror:reflect[dbms_name database_name username password host]
    ```
    __Obs__: if your DB connections are not default (localhost, root, no_password) :beers:

<br><br>
__Congratilation!__ your new app mirrored is up. :tada:

## Contributing

1. Fork it :twisted_rightwards_arrows: ( https://github.com/[my-github-username]/mirror_reflection/fork )
    * Create and check issues pending ([good issue pattern created example](https://github.com/MirrorReflection/rails_mirror_reflection/issues/12))
2. Create your :new: feature branch (`git checkout -b my-new-feature`)
3. Commit your changes :up: (`git commit -am 'Add some feature'`)
4. Push to the branch :repeat: (`git push origin my-new-feature`)
5. Create a new Pull Request :repeat_one:

## Useful guides for contributing 
1. [__How rails templates can be edited & how them work__](http://technology.stitchfix.com/blog/2014/01/06/rails-app-templates/)


## How does it work on the core :zap:
![Mirror WorkFlow Diagram](https://raw.githubusercontent.com/MirrorReflection/rails_mirror_reflection/master/modeling/diagrams/Mirror%20-%20WorkFlow.png)
