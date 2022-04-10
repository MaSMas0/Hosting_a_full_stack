# udagram Dependencies

### This is a full stack app using `PEAN` stack

## Database

The Database engine used here is `PostgreSQL`.
a free and open-source relational database management system emphasizing extensibility and SQL compliance. 
It was originally named POSTGRES, referring to its origins as a successor to 
the Ingres database developed at the University of California, Berkeley.


## API
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework
- [Typescript](https://www.typescriptlang.org/) - Typescript is a superset of Javascript


### Development
#### Main dependencies

1. Install [ExpressJs](https://expressjs.com/) to build server.

2. Install [body-parser](https://www.npmjs.com/package/body-parser) and [cors](https://www.npmjs.com/package/cors) as express middleware.

3. Install [pg](https://node-postgres.com/) for database.

4. Install [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) and [bcryptjs](https://www.npmjs.com/package/bcryptjs) for security.


### Code quality

1. Install [eslint](https://eslint.org/) and configure it to work with [typescript](https://www.typescriptlang.org/)

```bash
npm i -D eslint prettier eslint-config-prettier eslint-plugin-prettier  @typescript-eslint/eslint-plugin @typescript-eslint/parser
```


2. Create those files `.eslintrc`.

3. Open `.eslintrc` and fill it with those configurations.

```json
{
    "env": {
        "browser": true,
        "es6": true,
        "node": true
    },
    "extends": [
        "eslint:recommended",
        "plugin:@typescript-eslint/eslint-recommended",
        "plugin:@typescript-eslint/recommended"
    ],
    "globals": {
        "Atomics": "readonly",
        "SharedArrayBuffer": "readonly"
    },
    "parser": "@typescript-eslint/parser",
    "parserOptions": {
        "ecmaVersion": 2018,
        "sourceType": "module"
    },
    "plugins": [
        "@typescript-eslint"
    ],
    "rules": {
    }
}
```

## UI

Angular is a TypeScript-based free and open-source web application framework led by the Angular Team at Google
and by a community of individuals and corporations. 
Angular is a complete rewrite from the same team that built AngularJS

1. [Typescript](https://www.typescriptlang.org/) - Typescript is a superset of Javascript.

2. [Angular](https://angular.io/) - Angular is a TypeScript-based free and open-source web application framework.

3. [Ionic-native](https://ionicframework.com/) - Ionic is a complete open-source SDK for hybrid mobile app development .

### Development
#### Main dependencies

1. Install [Typescript](https://www.typescriptlang.org/) .

2. Install [Angular](https://angular.io/) .

3. Install [Ionic-native](https://ionicframework.com/) .

### Code quality


1. Install [eslint](https://eslint.org/) and configure it to work with [typescript](https://www.typescriptlang.org/)

```bash
npm i -D eslint prettier eslint-config-prettier eslint-plugin-prettier  @typescript-eslint/eslint-plugin @typescript-eslint/parser
```

2. Install eslint plugin specific for client projects.

3. Create those files `.eslintrc`.

4. Open `.eslintrc` and fill it with those configurations.

```json
{
    "env": {
        "browser": true,
        "es6": true
    },
    "extends": [
        "eslint:recommended",
        "plugin:@typescript-eslint/eslint-recommended",
        "plugin:@typescript-eslint/recommended"
    ],
    "globals": {
        "Atomics": "readonly",
        "SharedArrayBuffer": "readonly"
    },
    "parser": "@typescript-eslint/parser",
    "parserOptions": {
        "ecmaVersion": 2018,
        "sourceType": "module"
    },
    "plugins": [
        "@typescript-eslint"
    ],
    "rules": {
    }
}
```
