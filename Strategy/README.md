# Place individual specific strategies here.

How
------
### Download and unzip
Download additional [strategies](https://github.com/uzyn/opauth/wiki/List-of-strategies) and place them in directories here.
Remember to name the directory name as the actual name of the strategy. For example, place [Facebook strategy](https://github.com/uzyn/opauth-facebook) files in `./Facebook/` so that `FacebookStrategy.php` can be found at `./Facebook/FacebookStrategy.php`.

### Git submodule
If you prefer `git submodule`, you can simply run the following from the root dir without worrying about renaming:

```bash
git submodule add git://github.com/uzyn/opauth-facebook.git ./Strategy/Facebook
```

 More strategies
---------------
Check out the wiki for [more strategies](https://github.com/uzyn/opauth/wiki/List-of-strategies).