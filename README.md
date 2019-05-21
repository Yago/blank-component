# ⚛️ Blank React component

> Blank component when you need to create a new one.

## AiO

Made to work with :
- 👩‍🎤 [Emotion](https://emotion.sh/) for styles
- 📖 [Storybook](https://storybook.js.org) for doc
- 🧪 [Jest](https://jestjs.io) and [Enzyme](https://airbnb.io/enzyme/) for tests

Those are the full recommended dependencies (additional to [CRA deps](https://facebook.github.io/create-react-app/)) :

```sh
$ yarn add @emotion/core @emotion/styled @storybook/react @storybook/theming prop-types react react-dom enzyme enzyme-adapter-react-16 @babel/core babel-loader
```

## How to use

### 1. Use from Github

```sh
$ wget https://github.com/Yago/blank-component/archive/master.zip
$ unzip master.zip
$ mv ./blank-component-master/src/Blank ./path/to/components/Blank
$ rm -rf ./master.zip ./blank-component-master
```

### 2. Reuse from local

I recommend using [Generact](https://github.com/diegohaz/generact).

```sh
$ generact # and follow the steps
# or
$ mv ./path/to/components/Blank ./path/to/components/NewComponent
# Edit everything

```

### 3. New NPM scripts

You can also add the following scripts to your `package.json` :

```json
  "storybook": "start-storybook -p 6006",
  "build-storybook": "build-storybook",  
```

