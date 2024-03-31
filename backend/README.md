<!-- social media connecting shield -->

# Hotel Room Booking System (Backend)


## Installing Packages

```sh
# PACKAGES FOR BACKEND
npm i // install all dependencies
```

## Setup Development Environment


### 1. Install Global Dependencies

```sh
npm install -g npm@latest
npm install -g nodemon@latest
npx install -g win-node-env@latest
npx install -g jest@latest
```

### 2. Install Dev Dependencies

```sh
npm install -D eslint
npm init @eslint/config
npx install-peerdeps --dev eslint-config-airbnb-base
npm install -D eslint-plugin-node eslint-config-prettier eslint-plugin-prettier
```

### 3. Install Dev Dependencies for App Testing

```sh
npm install -D jest supertest superagent
npm install -D @babel/core @babel/preset-env babel-jest
jest --init // initialize jest for app testing
```


