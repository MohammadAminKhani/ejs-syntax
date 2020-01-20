# ejs-no2
98.10.30 include syntax | from tinyProjects

[This is final video!](https://www.aparat.com/v/ezR9a)

## packages
```
yarn add ejs express
```
## app.js (app.set)
```
app.set('view engine','ejs')
app.set('views','app/views')
```
## (module.exports) VS (module.exports > ejs)
```
res.send('<h2>Hello Dadashi!!</h2>')
res.render('index1')
```
## module.exports > ejs > include
```
<%- include('head.ejs') %>
```
