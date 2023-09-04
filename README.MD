# Creating a RESTful API with Node.js

This repository accompanies my YouTube video series on building a RESTful API with Node.js: [https://github.com/academind/node-restful-api-tutorial.git](https://github.com/academind/node-restful-api-tutorial.git)

## Usage

Check out the branch you're interested in (i.e. which belongs to the video in my series you just watched), `git clone` it and thereafter run `npm install`.

Make sure to also add your Mongo Atlas Admin Username to a nodemon.json file (which you have to create).

```
{
    "env": {
        "MONGO_ATLAS_PW": "YOUR_MONGO_USER_PW"
    }
}

MONGO_USER = <user>
MONGO_PASS = <pass>
MONGO_DBNAME = <dbname>
MONGO_CLUSTER = <cluster>
```

OLD version - packages need to be upgraded, refer package.json

"bcrypt": "^1.0.3",
"body-parser": "^1.18.2",
"express": "^4.16.2",
"jsonwebtoken": "^8.1.0",
"mongoose": "^4.13.5",
"morgan": "^1.9.0",
"multer": "^1.3.0"
--dev
"nodemon": "^1.12.1"
