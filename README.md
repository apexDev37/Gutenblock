# Gutenblock
> a custom block to _blockify_ the famous Hello Dolly, plugin

 <img src="https://novo-media.ch/app/uploads/2018/09/gutenberg-wordpress.jpg" width="25%" alt="WordPress + Gutenberg logo"/><img src="https://droitthemes.com/wp-content/uploads/2022/06/Hello-Dolly-WordPress-Theme.webp" width="25%" alt="Hello Dolly"/>

## Introduction
Gutenblock is a repository made to get-started with custom blocks targeted for the new
WordPress editor, [Gutenberg]. The custom block was developed locally using docker compose. Choosing the [Hello-Dolly] plugin is a great way for beginners to get started with block development. Follow the git commit [history] on how Gutenblock was created.
Share any comments, feedback, or inquires. I always love to hear and learn from the community❤

Learn more about developing custom blocks from the official [documentation].

## Installing / Getting started
This is an overview on the minimal setup needed to get started.

### Prerequisites
- [Git]
- [Docker]
- [Docker Compose]
- [Docker Desktop]
- [Node v14.0.0+]
- IDE/Code/Text editor (PHPStorm, VScode, Vim, etc)

Follow these tutorials on setting up Docker and Compose on either [Mac] or [Linux].
I'd recommend Microsoft's documentation to setup [Docker on WSL2] if you're on Windows. Use this [guide] to install on your host machine Node v14, which is the recommended version in the custom block developer handbook. 

### Local Setup
> The following setup was run on Ubuntu Focal (20.0.4 LTS)

Gutenblock has a single branch `main`.  
You can clone this repo with the following command.

- Clone repository
``` bash
    # cd your/desired/target/dir
    $ git clone https://github.com/apexDev37/Gutenblock.git
    $ cd Gutenblock
```

> This will clone the repository to a target dir on your host machine and navigate into its root dir.

### Configuration
Before running WordPress with docker compose, configure the required environment variables defined in the `./configuration` directory. Example `env` files are provided to configure the following instances: WordPress, MySQL, and phpMyAdmin.  
You can create `env` files with following code snippet.

- Create env files
``` bash
    # ensure your in the project root
    $ cd configuration/
    $ git clone https://github.com/apexDev37/Gutenblock.git
    $ cd Gutenblock
```



[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does
its job. There is no need to format nicely because it shouldn't be seen.
Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

<!-- Introduction links -->
[Gutenberg]: <>
[Hello-Dolly]: <>
[history]: <>
[documentation]: <>

<!-- Installing / Getting Started links -->
[Git]: <>
[Docker]: <>
[Docker Compose]: <>
[Docker Desktop]: <>
[Node v14.0.0+]: <>
[Mac ]: <>
[Linux]: <>
[Docker on WSL2]: <>
[guide]: <>
