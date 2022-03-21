# Shop CRM

This repo is related to the root directory on shopcrm

## Config
Create a directory and clone this repository on it, additionally clone the repo https://github.com/MazueraAlvaro/shopcrm-front, directory result example:


```bash
directory
    ├───shopcrm
    └───shopcrm-front
```

### Using Docker
To start using docker, move to shopcrm dir, copy the `.env.example` file to `.env` and set your owns values, then run `docker-compose build`, once the project is built to run up exec `docker-compose up -d`.