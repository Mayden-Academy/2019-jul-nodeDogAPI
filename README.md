# 2019-Jul-HotDog

# API for the Hot Dog app

## Initiate API

Install required packages: 

    npm install

Begin Server:

    node index.js

## Get All Dogs

Make ```GET``` request to ```/dogs```

Responds with json:

    {
        success: bool,
        message: 'XXXX',
        data: object (all Dogs info)
    }

## Update Winner

Make ```PUT``` request to ```/dogs```

Body should include a json with the following headers:

    {winnerID: string(MongoObjectID), winCount: integer}

