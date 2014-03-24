# &lt;x-giphy&gt;

Web Component wrapper for Giphy API

> Maintained by [Rob Dodson](https://github.com/robdodson).

![](https://media0.giphy.com/media/oFP9WKihsBjMs/giphy.gif)

## Demo

> [Check it live](http://robdodson.github.io/x-giphy).

## Usage

1. Install the component

  ```
  bower install x-giphy --save
  ```

2. Include platform.js:

  ```html
  <script src="bower_components/platform/platform.js"></script>
  ```

2. Import Custom Element:

  ```html
  <link rel="import" href="bower_components/x-giphy/x-giphy.html">
  ```

3. Start using it!

  ```html
  <x-giphy term="funny cat"></x-giphy>
  ```

## Options

Attribute   | Options   | Description
---         | ---       | ---
`key`       | *string*  | Your Giphy API key (defaults to [beta key][])
`term`      | *string*  | Find gif that matches this term
`random`    | *boolean* | Picks a random gif to display
`translate` | *boolean* | Uses Giphy "special sauce" to find matching gif
`gifId`     | *string*  | Displays the gif that matches this id

> [See demo page for code examples](http://robdodson.github.io/x-giphy).


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://robdodson.mit-license.org/) © Rob Dodson

[beta key]: https://github.com/giphy/GiphyAPI#access-and-api-keys
