# provision-cobol-dev-osx

Provision an instance of OS X with software to support software development using GNU COBOL. 

## Steps

The instructions assume you have a working instance of Apple OS X.

### Step 1 - Clone this repo

```shell
cd
git clone https://github.com/neopragma/provision-cobol-dev-osx
```

### Step 2 - Run the setup script

Run the setup script.

```shell
cd ~/provision-cobol-dev-ubuntu
./setup
```

### Step 7 - Verify the setup

The last thing the setup script does is to run a script named verify. Check the output from verify and see if any of the installation steps failed. If so, investigate and resolve the problems. If you discover a problem with the setup script, fix it and make a pull request.
