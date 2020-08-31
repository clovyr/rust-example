# About Clovyr Code

Clovyr Code delivers full-featured VSCode in the browser, connected directly to
any public or private git repository.

Learn more and try it out at [clovyr.app/code](https://clovyr.app/code)

Tip: Use `` CTRL+` `` to show/hide the terminal, and `CTRL+SHIFT+5` to open a new
terminal. [More shortcuts](https://help.clovyr.io/code/keyboard-shortcuts)

# Clovyr Code Rust examples

This repository includes sample Rust apps for the
purpose of demonstrating the Clovyr Code Rust development environment.

[TodoMVC](http://todomvc.com/) is a project which offers the same Todo application 
implemented in several popular programming languages.

## Running an example

1. Navigate to the example directory:  
`cd ~/git/github.com/clovyr/rust-example/examples/todomvc`
2. Compile the project:  
`cargo make build`
3. Run the server:  
`cargo make serve`
4. In a new browser tab, enter the url of your Clovyr Code instance
prefixed by `8080-`
   * The URL for your instance is found in the green bar at the bottom of
   the application space
   * For example, if your Code environment is `https://happy-otter.wnext.app`,
   the served application is at `https://8080-happy-otter.wnext.app`.
5. To stop the server, enter `CTRL+C` in the terminal where the program was
invoked

## Documentation

Find more documentation at https://help.clovyr.io.
