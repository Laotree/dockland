# Dockland

Yet another docker web ui.

## Requirements

* Ruby >= 1.9
* graphviz

## Usage

    git clone https://github.com/dynport/dockland.git /opt/dockland
    cd /opt/dockland
    bundle
    bundle exec ./bin/dockland -h <DOCKER_API_HOST>

    open http://127.0.0.1:9292

## To come

* fetch image graph in parallel
* add more information to frontend
* add features like:
  * cleanup dead containers
  * cleanup images without tags
  * ...
