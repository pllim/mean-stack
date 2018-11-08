# MEAN Stack Tutorial

This repository represents the end state of the tutorial.  The different branches of this repository correspond to checkpoints during the tutorial.   

## Installation
- Clone this repository
- `cd mean-stack`
- `npm install`
- Complete database setup (see below)
- `npm start`
- Visit http://localhost:3000

## Database Setup
`mongoimport --db ADASS --collection stars --file 100k_stars.csv --type csv --headerline`
