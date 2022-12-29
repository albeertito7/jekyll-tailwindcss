# Jekyll + TailwindCSS

This repository is aimed to be a template for those who want to use TailwindCSS in a Jekyll website.
This is a basic configuration using PostCSS and its plugin, TailwindCSS.

## Getting Started

Before anything, you should install the node module dependencies.

Just doing:

    $ yarn install

> Note: you can also use `npm`.

In this way, the PostCSS, TailwindCSS, and other dependencies will be included in your project.

Thus, enabling Jekyll to use them.

### Local

To run the application in your own local environment, you should install ruby.

There are many websites helping you out on this task. But you can check if you already got them by running:

    $ ruby -v
    
Afterwards, you should install Bundler and Jekyll:

    $ gem install bundler jekyll
    
And, to check them all:
    
    $ bundler -v
    $ jekyll -v
    
Also you can follow the oficial website steps if any doubt. Here the [link](https://jekyllrb.com/docs/installation/).

Finally, you just need to run:

    $ bundle exec jekyll serve

### Docker

To make the installation even easier, skipping the previous points,  just run

    $ docker-compose up

in this way you will use the original environment

> Note: remember to install [docker desktop](https://www.docker.com/products/docker-desktop)

## Project Structure

The following is a basic explanation about the Jekyll structure, and the TailwindCSS integration.

    ├── _data/
    ├── _drafts/
    ├── _includes/
    ├── _layouts/
    │       └── default.html  
    ├── _posts/
    ├── _sass/
    ├── assets/
    │       └── main.css 
    ├── .gitignore
    ├── CONTRIBUTING.md
    ├── Dockerfile        
    ├── Gemfile                 
    ├── Gemfile.lock
    ├── LICENSE                 <- MIT License.
    ├── README.md               <- The top-level README for the interested using this project.
    ├── _config.yml             <- Jekyll data configuration file.
    ├── docker-compose.yml
    ├── index.md                <- App entrance.
    ├── package.json            <- Node dependencies definition.
    ├── postcss.config.js       <- PostCSS module configuration.
    ├── tailwind.config.js      <- TailwindCSS plugin configuration.
    └── yarn.lock               <- Node dependencies specific versions.
