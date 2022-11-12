# debroot

Create a Debian chroot using interactive prompts.

## Usage

```
sudo apt install -y git
git clone https://github.com/TylerMS887/debroot ~/debroot
export OriginalWd="$(pwd)"
cd ~/debroot
chmod +x debroot
./debroot
cd $OriginalWd
```
