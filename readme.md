MAG SDK management
==================

## Usage ##

Install global dependencies:

```bash
sudo npm install -g meta
```

Get meta repo:

```bash
git clone https://github.com/magsdk/meta.git magsdk
# or for Github users with granted access
git clone git@github.com:magsdk/meta.git magsdk
cd magsdk
```

All preparations:

```bash
npm install
meta git update
meta npm install
sudo meta npm link --all
```


## Contribution ##

If you have any problems or suggestions please open an [issue](https://github.com/magsdk/meta/issues)
according to the contribution [rules](.github/contributing.md).


## License ##

`@magsdk/meta` is released under the [GPL-3.0 License](http://opensource.org/licenses/GPL-3.0).
