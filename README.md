# joi-ja

Joi's language.js file for Japanese. The translation is currently work in progress so any pull request is welcome if there's anyone willing to do this.

## Usage

Import the JSON file and specify that within the config when you validate.

```javascript
import joiJa from 'joi-ja'

Joi.validate(value, schema, {
    abortEarly: false,
    language: joiJa
})
```