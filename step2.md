# step 1
```
npm init -y
```
# step 2
```
npm install -D tailwindcss
```
# step 3
```
install tailwindcss @tailwindcss/postcss postcss  // if itis not working you can esiliy miss it
```
# step 4
* create style.css file and write
```
@import "tailwindcss";
```
# step 5
```
npx @tailwindcss/cli -i ./style.css -o ./output.css --watch
```

