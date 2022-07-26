# Middleman 4 + Tailwind CSS 3 Template

This repository contains a template that integrates [Tailwind CSS](https://tailwindcss.com/) 3 with [Middleman](https://middlemanapp.com/)

![Tailwind CSS 3 and Middleman Thumbnail](http://www.donnfelker.com/wp-content/uploads/2022/08/tailwindcss-and-middleman.png)
[Here is an article on how this template is built](https://www.donnfelker.com/tailwind-css-with-middleman/).

## Installation

 * Clone the repo
 * Run `npm install`
 * Run `bundle install`
 * Run `middleman serve` or `middleman build`

 Done!

## Usage

This installation uses Tailwind CLI via a [Middleman external pipeline](https://middlemanapp.com/advanced/external-pipeline/) ([source](https://github.com/donnfelker/middlemanapp-tailwindcss-template/blob/main/config.rb#L8)). 

When running `middleman serve` Tailwind CLI will watch for any changes to the content files and will then rebuild the CSS as necessary. 

When running `middleman build` the app will be built to the `build/` directory.


## Contributing

Bug reports and pull requests are welcome!

## License

The code is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
