Countastic
==========

Provides a twitter-like character counter for any text input or textarea.

+ [Website]

## Features

+ Provides a twitter-like character counter
+ Buttons are disabled when character limit is used
+ Callbacks on warning, alert and success
+ Pure javascript

## Usage

1. Download ```countastic.js``` then link it up on your project.

Example:
    <link rel="stylesheet" type="text/css" href="js/countastic.js"> 

2. Create a new instance

    ```shell
    new Countastic({
      countable: '#id_of_the_textarea_that_will_be_counted',
      counter: '#id_of_the_counter',
      button: '#id_of_the_button_that_will_be_disabled'
    })
    ```

## Roadmap

What's missing?

1. Highlighter for excess character (used in twitter)
2. Buggy counter
3. Documentation
4. Yadda yadda

## Contributing

1. Fork it
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request

## License

Crafted by Robbie Marcelo © 2013
<br/> Licensed under MIT [License]

=======


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/rbmrclo/countastic/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


[Website]: http://www.robbiemarcelo/countastic
[License]: http://opensource.org/licenses/mit-license.php
