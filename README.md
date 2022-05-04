## SMSWithoutBorders Gateway Client Packaging

### Dependencies

On Ubuntu

[Git](https://git-scm.com/)

```bash
sudo apt install git-all
```

Build-essential

```bash
sudo apt install build-essential
```

Devscripts

```bash
sudo apt install devscripts
```

Debhelper

```bash
sudo apt install debhelper
```

### Synopsis

```bash
./build <flag> [args]
```

### Flags

`-v` = Package version (float)

`-r` = Package release number (integer)

`-b` = Upstream release branch. Default (master)

`-h` = help

### Usage

```bash
./build -v [version number] -r [release number] -b [release branch]
```

### Logs

Build logs are found in the root directory in the form `{package_name}_{version_number}-{release_number}.build.log`
