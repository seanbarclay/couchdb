*WARNING:  this is a temporary solution for adding icons to the Icon Font. This will become a grunt task eventually.*

This is a temp solution till Fontcustom fixes this [BUG](https://github.com/FontCustom/fontcustom/issues/172)<br>

### Installation

Requires **Ruby 1.9.2+**, **FontForge** with Python scripting.

```sh
# On Mac
brew install fontforge eot-utils
cd [LOCAL_COUCHDB_REPO]/src/fauxton/assets/fonts
bundle
```

That should install the gem in a path like below:
/Users/[USERNAME]/.rvm/gems/[RUBYVERSION]/bundler/gems/fontcustom

Don't forget to update `fontcustom.yml` with the correct paths where it says `PUT_YOUR_PATH_HERE`.

From there, you can run the command `fontcustom compile` to compile the svgs located in the ./icons directory into updated fauxtonicon font files. 


For more info on Fontcustom, check out their documenation: [Fontcustom documentation](https://github.com/FontCustom/fontcustom)

[Licenses](https://github.com/FontCustom/fontcustom/blob/master/LICENSES.txt)