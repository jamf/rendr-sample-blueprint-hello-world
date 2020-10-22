# `rendr` sample blueprint: Hello, World!

A minimal Hello World blueprint for [rendr](https://github.com/jamf/rendr/)

## Usage

Create a project from the blueprint:

    rendr init hello --blueprint https://github.com/jamf/rendr-sample-blueprint-hello-world

Check out the functionality of your new project:

    cd hello
    ./hello.sh
    > Hello, world!

The blueprint can be customized with a different name to use for the greeting, by providing the `name` value:

    rendr init hello --blueprint https://github.com/jamf/rendr-sample-blueprint-hello-world --value name:foo
    cd hello
    ./hello.sh
    > Hello, foo!
