# Monkeytronics

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

## Getting Started

### Dependencies

* Install node version >= 20.17.0
* Install yarn globally >= 4.0.1
* Install nx v16.6.0 globally (If encountring issues on Silicon based chips, install with npm install -g nx)

### Installing

* Run `yarn install` in the root directory

## Run Project

* For running Airsmart-User:
```
npx nx serve airsmart-user
```
* For running storybook in Airsmart-User:
```
npx nx run airsmart-user:storybook
```
* For running Airsmart-User on Android:
```
npx nx run build airsmart-user
```
```
npx nx run airsmart-user:sync:android
```
```
npx nx run airsmart-user:open:android
```
`cd apps/airsmart-user` && `yarn install`
* For running Airsmart-User on IOS:
```
npx nx run build airsmart-user
```
```
npx nx run airsmart-user:sync:ios
```
```
npx nx run airsmart-user:open:ios
```
`cd apps/airsmart-user` && `yarn install`

### Production Build

* For Airsmart-User:
```
npx nx build airsmart-user
```
* For storybook in Airsmart-User:
```
npx nx run airsmart-user:build-storybook
```