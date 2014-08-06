# &lt;x-imdb&gt;

A Polymer element to display information from IMDB.

> Maintained by [Neil Kistner](https://github.com/wyze).

## Demo

> [Check it live](http://wyze.github.io/x-imdb).

## Installation

Using [Bower](http://bower.io), run:

```shell
bower install x-imdb --save
```

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.3.4/polymer.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="x-imdb.html">
    ```

3. Start using it!

    ```html
    <x-imdb><x-imdb>
    ```

## Examples

Display information from IMDB for 'The Social Network':

```
<x-imdb imdbid="tt1285016"><x-imdb>
```

## Setup

In order to run it locally you'll need a basic server setup.

1. Install [NodeJS](http://nodejs.org/download/).
2. Install [GruntJS](http://gruntjs.com/):

    ```sh
    $ npm install -g grunt-cli
    ```

3. Install local dependencies:

    ```sh
    $ npm install
    ```

4. Run a local server and open `http://localhost:8000`.

    ```sh
    $ grunt connect
    ```

## Options

Attribute | Options  | Default | Description
---       | ---      | ---     | ---
`imdbid`  | *string* | `null`  | The IMDB ID of the movie to display.
`layout`  | *string* | `debug` | Changes the way the data is displayed.


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](LICENSE)
