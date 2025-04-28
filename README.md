> ⚠️ **This repository is archived and kept for reference purposes only.**  
> It is no longer maintained and will not receive updates or support.

# Sample Function: Node.js Calculator

## Introduction

This repository contains a simple calculator showing how to use state, Node.js packages, HTML, and functions. You can deploy it on DigitalOcean's App Platform as a Serverless Function component. Documentation is available at https://docs.digitalocean.com/products/functions.

### Requirements

* You need a DigitalOcean account. If you don't already have one, you can sign up at [https://cloud.digitalocean.com/registrations/new](https://cloud.digitalocean.com/registrations/new).
* To deploy from the command line, you will need the [DigitalOcean `doctl` CLI](https://github.com/digitalocean/doctl/releases).
* This project uses a Redis instance to maintain state. You will need to provision a DBaaS instance and provide the `DATABASE_URL` credentials to deploy and use the function.

### Learn More

You can learn more about Functions and App Platform integration in [the official App Platform Documentation](https://www.digitalocean.com/docs/app-platform/).
