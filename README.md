This is a script I wrote to make managing Discord installation easier (without using any package managers, so it should work on any distro).

Features:
- Install the latest Discord client from the official .tar.gz package
- Update existing installation
- Uninstall
- Remove the user data folder
- Optionally run the postinst.sh provided by Discord (or always, automatically if you set that in the overrides menu)
- Keep your overrided settings in json file

You can use overrides menu to make it create an activator with '--no-sandbox' parameter. That might be useful on Ubuntu distros.

Tested on Ubuntu 25.04, Mint 22.2

Dependencies:
tar, gzip, wget, jq (optional)
The script will tell you miss something

I provide this script as is. I do not take any responsibility if it malfunctions, etc.
You use it at your own risk.
