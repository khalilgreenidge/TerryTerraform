# Terry The Terraform Repo 

![alt](https://slackmojis.com/emojis/2116-terraform/download)

Welcome to my first Terraform repo. This repo consist of my configuration files used inconjunction with a Docker container. It creates and configures and provisions a NGINX webserver container.


## Getting Start
First, clone the repo:

```bash 
git clone https://github.com/khalilgreenidge/TerryTerraform.git
```

Install the providers (in this case docker):
```bash
terraform init
```

Apply the configuration
```bash
terraform apply
```

Go to [localhost:8000/](http://localhost:8000/) in your browser



