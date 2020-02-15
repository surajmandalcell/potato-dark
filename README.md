# Potato Dark [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/surajmandalcell/potato-dark/blob/master/license.md) 

Potato Dark is a modern, simple and beautiful Hugo theme.

![screenshot](https://github.com/surajmandalcell/potato-dark/blob/master/images/screenshot.png)   

## Overview

* Support for tags
* Responsive design
* Support for Related Content
* Analytics with Google Analytics
* Modern, Simple and beautiful design
* Medium's Image Zoom（[zoom.js](https://github.com/fat/zoom.js/))
* Social links （most social networks available）

Use short code for Image Zoom.

```
{{% zoom-img src="/images/default.jpg" %}}
```

## Installation

Inside the folder of your Hugo site run:

```shell
$ git submodule add https://github.com/surajmandalcell/potato-dark themes/potato-dark
```

Or download it from the [release](https://github.com/surajmandalcell/potato-dark/tree/release) branch



Then,  
  
replace your `config.toml` with the one provided in `themes/potato-dark/exampleSite/config.toml`

## Usage

Use hugo's -t potato-dark or --theme=potato-dark option with hugo commands. Example:

```shell
$ hugo server -t potato-dark -w -D
```

## Configuration

You may specify following options in `config.toml` of your site to make use of
this theme's features.

For getting started with potato dark, copy the [config.toml](https://github.com/surajmandalcell/potato-dark/blob/master/exampleSite/config.toml) file from the exampleSite directory inside Potato's repository to your site repository.

```shell
$ cp themes/potato-dark/exampleSite/config.toml .
```

Now, you can start editing this file and add your own stuff!

## Contributing

Pull requests, bug fixes and new features are welcome!

To start just fork the repository and consider creating an seperate random branch so it get easier for me to test and review pushed code! thanks.

<!-- ## Development

1. Edit the theme or fix somthing
2. Create a pull request and be patient -->

## License

Open sourced under the MIT license.
