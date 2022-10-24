mkadindex
=========

By Rémino Rem <https://remino.net/>

Create .htaccess file for Apache HTTPd to show a stylised directory index.

[Code & Download](https://github.com/remino/mkadindex/)

- [Getting Started](#getting-started)
	- [Installation](#installation)
		- [Using Homebrew on macOS](#using-homebrew-on-macos)
		- [Using git](#using-git)
		- [Using cURL](#using-curl)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)



## Getting Started

### Installation

#### Using Homebrew on macOS

```sh
brew tap remino/remino
brew install mkadindex
mkadindex -h
```
#### Using git

```sh
git clone https://github.com/remino/mkadindex.git
cd mkadindex
./mkadindex -h
```

#### Using cURL

```sh
curl -L https://github.com/remino/mkadindex/raw/main/mkadindex > mkadindex
chmod +x mkadindex
./mkadindex -h
```

[Back to top](#mkadindex)



## Usage

```
mkadindex 1.0.0

USAGE: mkadindex [<options>] [<outputdir>]

Create .htaccess file for Apache HTTPd to show a stylised directory index.

Will output to current directory if no outputdir is specified.

OPTIONS:

	-c        Clear .htaccess file if it exists.
	-h        Show this help screen.
	-t        Specify title for directory. (Default: Download)
	-v        Show script name and version number.

```

[Back to top](#mkadindex)



## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[Back to top](#mkadindex)



## License

Distributed under the ISC License. See `LICENSE.txt` for more information.

[Back to top](#mkadindex)
