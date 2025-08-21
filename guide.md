# Guide to convert document

## kramdown-rfc2629

1. Install Ruby

```bash
sudo apt update
sudo apt install ruby-full
```

2. Install kramdown-rfc2629

```bash
gem install kramdown-rfc2629
```

3. Convert

```bash
kramdown-rfc2629 draft-shim-example-00.md
```

## xml2rfc

1. Install xml2rfc

```bash
sudo apt update
sudo apt install xml2rfc
```

2. Convert

```bash
xml2rfc draft-shim-example-00.xml
```

## Upload to IETF

https://datatracker.ietf.org/submit
