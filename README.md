# sgb.bond

This project hosts the website for https://sgb.bond

## Developments

### Requirements

#### Install gomplate:

```bash
go install github.com/hairyhenderson/gomplate/v3/cmd/gomplate@latest
```

#### Steps to update index.html:

```bash
cat index.tmpl.html | gomplate -d sgb=./sgb.json > index.html
```