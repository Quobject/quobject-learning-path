
http://localhost:8081/index.html




## 1:
```
npx tsc -w
```
## 2:
```
npx onchange "./dist/**/*.js" -- node ./spec/runjasmine.js
```

## 3:
```
npx reload -d ./spec/results report.html
```

http://localhost:8080/report.html





