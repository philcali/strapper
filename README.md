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
./serve
monido src/ -e build
```
