
# Hook's Cowsay

This is a simple cowsay clone written in [Hook](https://github.com/fabiosvm/hook-lang) to demonstrate how packages work.

## Installation

Use the package manager [hpkg](https://github.com/hook-lang/hpkg) to install Hook's Cowsay.

Run the following command to install this package as a dependency of your project:

```
hpkg install cowsay
```

## Usage

Now you can use it in your Hook project:

```js
import cowsay;

cowsay.say("Hello, world!");
```

The `say` function accepts a message and prints the cow saying it to the console. Like this:

```
-----------------
< Hello, world! >
-----------------
       \   ^__^
        \  (oo)\_______
           (__)\       )\/\
               ||----w |
               ||     ||
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
