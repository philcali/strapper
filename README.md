# Static Bootstrap Suite 

A combination of lmxml and node for some quick bootstrapping.

## Requirements

- conscript
- node / npm

## Installation

```
git clone git://github.com/philcali/strapper.git
cd strapper

# Get lmxml trans compiler
cs philcali/lmxml
cs philcali/monido

# Get coffee-script because why not?
npm install -g coffee-script
```

## Usage

```
./install
# Enter your full gii project repo
./tools/serve
monido src/ -e tools/build
```

## Start Strapping

Copy the following to `src/index.lmxml`:

```
html
  head title "Strapped"
  body h1 "Not enough time!"
```

Monido will pick up the change and transpile the lmxml to html.

```
<html>
  <head>
    <title>Strapped</title>
  </head>
  <body>
    <h1>Not enough time!</h1>
  </body>
</html>
```
