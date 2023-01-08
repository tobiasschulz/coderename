# coderename

## Setup

### Install dependencies

```bash
cpan App::cpanminus

source ~/.bashrc

cpanm List::Permutor
```

## Run


```bash

./coderename.pl "Word Abc Def" "Xyz 123"
./coderename.pl "Word AbcDef" "Xyz 123 456"


```

## Example

```bash
../../coderename/coderename.pl "NowyCitizenPortal" "Nowy CitizenPortal" && \
../../coderename/coderename.pl "Nowy CitizenPortalWasm" "Nowy CitizenPortal Wasm" && \
../../coderename/coderename.pl "Nowy CitizenPortalWeb" "Nowy CitizenPortal Web" && \
../../coderename/coderename.pl "Nowy CitizenPortalShared" "Nowy CitizenPortal Shared"
```

