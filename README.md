## How to publish a package

- Update the version in package.json file
- Build

```
npm run publish:npm
```

- Login

```
npm login --registry=https://npm.pkg.github.com
Username: nouredu
Password: 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
Email: wesam.nouredu@gmail.com
```

- Run

```
npm publish
```

- Check the package under this link: https://github.com/nouredu/questions-design/packages

## How to use the package

- Login to npm as in the previous part
- Use the last version of the package in your package.json file

```
e.g. "@nouredu/react-clock": "^4.0.0"
```

## Resources

[configuring npm for use with github packages](https://help.github.com/en/packages/using-github-packages-with-your-projects-ecosystem/configuring-npm-for-use-with-github-packages)
