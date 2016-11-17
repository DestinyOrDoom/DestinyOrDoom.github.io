# Doom or Destiny

## Setting up the necessary environment

1. Install latest version of Ruby [http://rubyinstaller.org/downloads/](http://rubyinstaller.org/downloads/)
1. Add Ruby to your PATH [http://stackoverflow.com/questions/26947427/how-do-i-add-ruby-to-the-path-variable-on-windows](http://stackoverflow.com/questions/26947427/how-do-i-add-ruby-to-the-path-variable-on-windows)
1. Fix the SSL Certificate issues by following [https://gist.github.com/eyecatchup/20a494dff3094059d71d](https://gist.github.com/eyecatchup/20a494dff3094059d71d)
1. Install Jekyll tools locally, by running `bundler install`
1. Install a Git client, such as [SourceTree](https://www.sourcetreeapp.com/)
1. Clone this repository from GitHub to your computer
 
## Testing

Run

```
bundler exec jekyll serve
```

You should find the website at [http://127.0.0.1:4000](http://127.0.0.1:4000/).

## Information

Much of the content is generated based on the data files in `_data` -folder. E.g. any `.yml` file in the `_data` -folder that has the characters `show--` in it's filename is assumed to define another show. They are processed generally in alphabetical order.

Using:
 
 - [Milligram CSS framework](https://milligram.github.io/)
 - [Liquid templates](https://github.com/Shopify/liquid/wiki/liquid-for-designers)

