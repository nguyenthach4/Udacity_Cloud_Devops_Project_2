# CD12352 - Infrastructure as Code Project Solution
# Nguyen Thach - Account: NguyenT4

## Spin up instructions
### Root project
cd starter/
### Network
./create.sh createnetwork network.yml network-parameters.json
### Udagram
./create.sh createudagram udagram.yml udagram-parameters.json

## Tear down instructions
### Network
./update.sh createnetwork network.yml network-parameters.json
### Udagram
./update.sh createudagram udagram.yml udagram-parameters.json

## Other considerations
    http://create-webap-5vau8qierugl-1238507648.us-east-1.elb.amazonaws.com/