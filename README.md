# OCT Power Monitoring Test Deployment

Files for OCT power monitoring. Initial project deployment uses docker compose for easy troubleshooting and temporary deployment. This will likely live in a kubernetes cluster long-term.

## Environment Setup

1. Create `prometheus-ipmi/ipmi_remote.yml` - an example file is available in that directory and usually only user and pass has to be updated.
1. `docker compose up` to run the containers
