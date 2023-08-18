# Documentation

## Using ng to create project

- Installing angular cli

```
npm install -g @angular/cli
```

- Creating Angular App

```
ng new myApp
```

## Using npm to create project

- Creating Angular App
  if "npm --version" > 8.5.0:

```
npm init @angular myApp
```

# Default App

- Install dependencies

```
npm install
```

- Build and Serve the app

```
ng serve
```

# Creating Componnent

- Creating component called "home"

```
ng generate component home --standalone --inline-template --skip-tests
```

# Creating Interface

- Creating interface called "home"

```
ng generate interface home
```

# Creating Service

- Creating service called "home"

```
ng generate service home
```

# Json-server

- Installing

```
npm install -g json-server
```

- Starting

```
json-server --watch db.json
```
