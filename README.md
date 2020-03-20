----Project 2----
## TABLES
1) ANIMALS
Species Name
Life Expectancy
Animal ID

2) Habitats
Environment
Habitat ID

3) Lives_In
Animal ID
Habitat ID

4) Can Hunt
Animal Predator ID
Animal Prey ID

## Launch API
-- npm i, npm start / nodemon in Terminal
-- local host is on port 9000

## CRUD OPERATIONS
1) GET
http://localhost:9000/ --> homepage
http://localhost:9000/animals --> Animals List
http://localhost:9000/habitats --> Habitats List
http://localhost:9000/animals/1 --> Animal # 1
http://localhost:9000/habitats/1 --> Habitat # 1

2) POST
http://localhost:9000/animals
OR
http://localhost:9000/habitats

Require JSON format in Body of HTTP request
{
  "species_name": "Some kind of test",
  "life_expectancy": 15
}

3) PUT
Also requires JSON format in request

http://localhost:9000/animals/1 --> Update Animal # 1
http://localhost:9000/habitats/1 --> Update Habitat # 1

4) DELETE

http://localhost:9000/animals/1 --> Delete Animal # 1
http://localhost:9000/habitats/1 --> Delete Habitat # 1

## Technologies Used
-- Express
-- Node JS / Nodemon
-- Postman
-- SQLITE 3
-- DB Browser

## Next Steps
-- Stretch 1) Add user front HTML/CSS
-- Stretch 2) Implement synchronous seed file
-- Stretch 3) Put all verbs into separate routers / organize index.js
