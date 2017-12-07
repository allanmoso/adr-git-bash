# ADR in Git Bash

## ADR Tools

Download ADR Tools from [npryce/adr-tools](https://github.com/npryce/adr-tools)

```
mkdir -p ~/bin
cd ~/bin
curl -L https://github.com/npryce/adr-tools/archive/2.1.0.tar.gz | tar zx
```

## Alias
Add a new alias for convenience
```
echo "alias adr=~/bin/adr-tools-2.1.0/src/adr" >> ~/.bash_profile
```

Now you can run the adr-tools doing the following:
```
adr
```
