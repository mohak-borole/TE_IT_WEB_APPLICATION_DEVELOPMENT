### S1:
cd project-directory

### S2:
> npm install
> npm --version
### S3:

> npm init
> npm install express --save
### S4:

go to project directory
create folder named "public"
add index.html , index.css

create a atatic website by editing these files.

### S5:
go to index.js (outside public folder)

add following code in index.js
>const express = require("express");</br>const app = express();</br>app.use(express.static("public"))</br>app.listen(4000 , ()=>{</br>    console.log("Server has started");</br>})

### S6:
>npm index.js

### S7:
on the browser , go to https://localhost:4000

#### *EXTRA*:
Make cahnges to index.html and index.css to make the website more attractive.