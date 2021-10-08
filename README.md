# Please note

This project is **alpha** quality. We don't yet guarantee stability, data integrity or a clean upgrade path. Only use this project if you are interested in experimenting with it.

# Monitor-analytics fromedwin

This project is a monitoring analytics for the monitor [fromedwin project]().


## Installation

[Docker](https://www.docker.com/) and [Docker-compose](https://docs.docker.com/compose/) are required to run this project.

### Dependancies

```bash
  sudo apt install python3-pip apache2-utils
```

## Run Locally

Clone the project

```bash
  git clone https://github.com/fromedwin/monitor-analytics.git
```

Go to the project directory

```bash
  cd monitor-analytics
```

Start the server

```bash
  ./run.sh
```
  
## Environment Variables

No variables are required to run locally, but might be needed to configure your production environment

You will need to add the following environment variables to your `.env` file

`PORT` *(default: 8001)*

`SERVER_PROTOCOL` url used to generate letsencrypt SSL certificate and access the application

`SERVER` secret key used by django's session

`WEBAUTH_USERNAME` username to protect none public access

`WEBAUTH_PASSWORD` password to protect none public access

  
## Feedback

If you have any feedback, please reach out to us at fromedwin@sebastienbarbier.com

  
## License

[MIT](https://choosealicense.com/licenses/mit/)
