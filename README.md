# joi-ja

Joi's language.js file for Japanese. The translation is currently work in progress so any pull request is welcome if there's anyone willing to do this.

## Install

```bash
$ yarn install joi-ja

# Or

$ npm i --save joi-ja
```

## Usage

Import the JSON file and specify within the config when you validate.

```javascript
import joiJa from 'joi-ja'

Joi.validate(value, schema, {
    language: joiJa
})
```