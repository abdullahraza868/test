# Monkeytronics

<a alt="Nx logo" href="https://data.monkeytronics.co.nz/" target="_blank" rel="noreferrer"><img src="https://images.squarespace-cdn.com/content/v1/5407f3c8e4b0d384103c4348/f45154e3-fbca-40d5-a5ca-355f3e6cf87e/Monkeytronics-Full_Logo.png?format=1500w" width="45"></a>

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