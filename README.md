# Shop CRM

This repo is related to the root directory on shopcrm

## Config
Create a directory and clone this repository on it, additionally clone the following repos: 

- https://github.com/MazueraAlvaro/shopcrm-front
- https://github.com/MazueraAlvaro/shopcrm-back

Directory result example:

```bash
directory
    ├───shopcrm
    ├───shopcrm-back
    └───shopcrm-front
```

### Using Docker
To start using docker, move to shopcrm dir, copy the `.env.example` file to `.env` and set your owns values, then run `docker-compose build`, once the project is built to run up exec `docker-compose up -d`.