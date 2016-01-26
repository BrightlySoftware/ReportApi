# DudeReportApi

Special thanks [API Blueprint Focus Booster](https://github.com/saamo/api-blueprint-focus-booster)

## Getting Started:

Install [Node.js](https://nodejs.org) and [Gulp](http://gulpjs.com)

Git teh codez
```bash
git clone https://github.com/DudeSolutions/DudeReportApi.git
```

Install node dependencies
```bash
npm install
```

Build the apiary.apib
```bash
gulp
```

## Source Layout
```
./src
  /_header            // dude header and heartbeat
    /_header.apib     
    /heartbeat.apib   
  /controllers        // a REST collection per file
    /controller.apib  
  /models             // a model per file
    /_header.apib     // Sets up "Data Structures"
    /class.apib
```
