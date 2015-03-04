# Stem

A [Middleman](http://www.middlemanapp.com) starter template

## Use

Create a directory `mkdir ~/.middleman` 

Clone and Stem to that directory `cd ~/.middleman && git clone git@github.com:woodall/stem.git` 

Run 

`$ middleman init your_app_name --skip-gemfile --skip-bundle --template=stem`


### Make it easier to start

Add the following to your `.bash_profile`

`stem () { middleman init "$@" --skip-gemfile --skip-bundle --template=stem; }`

Then you can run

`$ stem your_app_nam`

## Bundle install

Bundle is skipped so you'll need to

`cd your_app_nam && bundle exec bundle install`
