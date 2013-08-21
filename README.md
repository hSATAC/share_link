# ShareLink

This is a tool of sharing links to twitter from command line.

It will grab title and decription from url, send them into vim. After editing, tweet will be sent via gem `t`. So make sure you've set `t` correctly.

See it in action: http://ascii.io/a/5072

## Installation

Clone this repository and build, install yourself.

    $ bundle exec rake install

## Usage

    $ share_link <url>

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## TODO

1. Customizable install path
2. Customizable fetch result pattern. ex `"#{title} #{url} #{description}"`
3. Support more editors, preferbaly `$EDITOR`
4. Customizable send endpoints.
