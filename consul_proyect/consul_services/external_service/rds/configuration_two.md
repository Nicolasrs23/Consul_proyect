#consul rds service

Here we have, a check by the name TCP inside the service configuration register via 

curl --request PUT --data @rds.json localhost:8500/v1/catalog/register

The output of consul is a 

dial tcp 10.0.5.96:5432: i/o timeout

##The intentions is set to allow everything 