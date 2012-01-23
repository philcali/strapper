# Static Bootstrap Suite 

A combination of lmxml and node for some quick bootstrapping.

## Requirements

- conscript
- node / npm

## Installation

```
git clone <repo>
cd <repo>

# Get boostrap
git submodule init
git submodule update

# Get lmxml trans compiler
cs philcali/lmxml
cs philcali/monido

# Get 
npm install -g coffee
npm install express
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
