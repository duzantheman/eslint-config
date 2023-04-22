# @duzantheman/eslint-config

My central ESLint config

## Install

```
npm i -D \
  @duzantheman/eslint-config \
  @typescript-eslint/eslint-plugin \
  eslint \
  eslint-plugin-prettier \
  eslint-plugin-promise \
  <!-- Only install the following if you're using eslint-config/web -->
  eslint-plugin-react \
  eslint-plugin-react-hooks
```

## Usage

Add this to your `package.json` file:

```json
"eslintConfig": {
  "extends": "@duzantheman/eslint-config/web"
}
```

or in your `.eslintrc` file:

```json
{
  "extends": "@duzantheman/eslint-config/web"
}
```
