
[![Web Build and Deploy](https://github.com/alphasofthub/resume/actions/workflows/build.yaml/badge.svg)](https://github.com/alphasofthub/resume/actions/workflows/build.yaml)

# Resume

Let's build your resume on GitHub page.

*The Product of **[AlphaSoftHub Pvt Ltd](http://alphasofthub.com/)***
  

## How to build

1. Click Use this repo as shown below
	![enter image description here](https://i.imgur.com/1D1fu32.png)
2. Go to `Actions` tab and enable to run workflow **If not enable** like below
	![enter image description here](https://i.imgur.com/CYHv4Ar.png)
3.  Create [Personal Token](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) 
4. Add your `personal token` to your repo `Secret` Store
5. Click `Settings` => `Secrets` => `New secret` fill the form, `name` will be `TOKEN` `value` will be your `personal token`
6. Update `data.js` file according to your info and push the changes into GitHub.
7. That's all.
8. Now you can visit it with `https://your_username.github.io/resume`

## Features
1. Open Source
2. Fully Customizable

## Todo
1. Add more templates.

## License
MIT

  
## Contribution
You're welcome to contribute to this project. You should follow contribution guideline  [Contribution guideline](https://github.com/alphasofthub/resume/blob/main/CONTRIBUTING.md)

## Run locally
```
npm install
```
```
npm run watch
```
#### Compiles and minifies for production

```
npm run build
```
 
