# Click with OIDC support
-----
Click is the Command Line Interactive Controller for Kubernetes.
Its purpose is to manage a large number of Kubernetes clusters/objects quickly and efficiently.

This repository was forked from [https://github.com/databricks/click](https://github.com/databricks/click)
and adds support for OpenID Connect Authentication Provider.

Works together alongside with [https://github.com/int128/kubelogin](https://github.com/int128/kubelogin) 

## Demo Screencast
![A demo gif that shows a few features](https://imgur.com/ft4WHcL.gif)

## Installation

1. You'll need rust and cargo. See 
[here](https://doc.rust-lang.org/cargo/getting-started/installation.html) for instructions on how to
get them.

2. Clone this repository and build via `cargo build`

3. Add built `click` to your `PATH`, eg. via `sudo cp target/debug/click /usr/local/bin`
