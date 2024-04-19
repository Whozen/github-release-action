# github-release-action

Version: 0.1.13

Create and test Github workflow to create new release. The workflow should:
1. Generate new tag based on user input (Major, Minor or Patch)
2. Verify if the bumped version matches version in package.json file.
3. Generate release notes automatically
4. Take user input for release name or automatically generate it by default if no user input.
5. Create Github release.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
