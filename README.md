# Polish Translations for Admin-on-rest

Polish translations for [admin-on-rest](https://github.com/marmelab/admin-on-rest), the frontend framework for building admin applications on top of REST services.

![admin-on-rest demo](http://static.marmelab.com/admin-on-rest.gif)

## Installation

```sh
npm install --save aor-language-polish
```

## Usage

```js
import polishMessages from 'aor-language-polish';

const messages = {
    'pl': polishMessages,
};

<Admin locale="pl" messages={messages}>
  ...
</Admin>
```

## License

This translation is licensed under the [MIT Licence](LICENSE).
