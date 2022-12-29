# Jekyll + TailwindCSS

This repository is aimed to be a template for those who want to use TailwindCSS in a Jekyll website.
This is a basic configuration using PostCSS and its plugin, TailwindCSS.

## Getting Started

### Local

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
