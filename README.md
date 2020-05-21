# api-generator

### Prepare
> 1. node.js
> 2. npm

### Demand
> Use just one line code to generate a template file, there is a API file template.
> (Just a template file! You have to change some arguments or options to fit your demand.)

### Usage
```nodejs
git clone git@github.com:castelain/api-generator.git
cd ./api-generator
npm install
cd ./src
// It will create a template named template.js in current directory.
 ./index.js -d template.js -e User
```

### Tips
> In fact, you can replace the template that you want to generate. The only thing you need to keep in mind is that using `{%[any word]%}` as the placeholder in your owner init template file.
