# init.js

[![Current tag](http://img.shields.io/github/tag/[GitHubUsername]/init.js.svg)](https://github.com/frdmn/init.js/tags) [![Repository issues](http://issuestats.com/github/frdmn/init.js/badge/issue)](http://issuestats.com/github/frdmn/init.js)

![](http://up.frd.mn/755Ry.gif)

A simple NodeJS based command line utility to quickly initialize a developer workspace / git repository including README templates and license files.

## Installation

1. Make sure you've installed all requirements
2. Install the project globally using `npm`:  
  `npm install -g init.js`

## Usage

* Create a new folder for your new project:  
  `mkdir test-project`  
* Change into that directory:  
  `cd test-project`  
* Run `init.js`:  
  `init`  

You can optionally pass the following arguments:

```
Usage: init [options]

Options:
  -h, --help        Show help and usage information
  -v, --version     Display version information                                                 [default: false]
  -i, --ignore-git  Ignore existing .git folder in the current directory, can be true or false  [default: false]
```

## Contributing

1. Fork it
2. Create your feature branch:  
  `git checkout -b feature/my-new-feature`
3. Commit your changes:  
  `git commit -am 'Add some feature'`
4. Push to the branch:  
  `git push origin feature/my-new-feature`
5. Submit a pull request

## Requirements / Dependencies

* NodeJS
* Existing `.gitconfig`

## Version

1.1.0

## License

[MIT](LICENSE)
