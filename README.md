# AskOmics website for you

[![Build Status](https://travis-ci.org/askomics/website.svg?branch=master)](https://travis-ci.org/askomics/website)

AskOmics website it is, build with [Nikola](https://getnikola.com/)


## Installation

### Install dependencies

```bash
# Debian/Ubuntu
sudo apt install -y git make python3 python3-venv
# Fedora
sudo dnf install -y git make python3 python3-virtualenv
```

### Download and install website

```bash
git clone https://github.com/askomics/website.git askomics_website
cd askomics_website
make install
```

## Deployment

```bash
make build
```

Generated html are in the `output` directory


## Developement

### Serve website locally

```bash
make serve
```

### Create a page

```bash
make page
```

The new page will be created in the `pages` directory

### Create a post

```bash
make post
```

The new post will be created in the `posts` directory
