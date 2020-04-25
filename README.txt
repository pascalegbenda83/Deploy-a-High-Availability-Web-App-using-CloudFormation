
PASCAL EGBENDA | UDACITY PROJECT-2
This ptoject deploys a high available web application using cloud formation templates.

DEPLOYING THE NETWORK TEMPLATE
> ./create.sh Network network-infrastructure.yml network-infrastructure-parameters.json

DEPLOYING THE BASTION-HOST TEMPLAATE

> ./create.sh Bastion-Servers Bastion-Host.yml Bastion-Host-parameters.json

DEPLOYING THE WEBAPP TEMPLATE
> ./create.sh WebApp WebApp.yml WebApp-parameters.json

