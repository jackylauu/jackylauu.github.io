# [jackylauu.github.io (Preview here)](https://jackylauu.github.io)

This is forked from [Jaan Altosaar](https://jaan.io)'s fork of [Cole Townsend](http://coletownsend.com)'s [Balzac](https://github.com/ColeTownsend/Balzac-for-Jekyll). Major thanks to them!

## Setup 
Make sure you have ruby installed and install bundler for managing gems:
`gem install bundler`.
Install the dependencies:
`bundler install`.
Then you should be able to run jekyll commands:
`jekyll build`

## Testing locally

`jekyll serve --config _config.yml,_config_dev.yml --watch`

`scss -t compress assets/sass/i.scss assets/css/i.css`

Check for broken internal and external links:
`rake test`


