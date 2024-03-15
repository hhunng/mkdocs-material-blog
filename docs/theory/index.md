# Networking on AWS


## VPC Flow Logs

![Logs](./images/001-flowlogs.png)
![Logs](./images/002-flowlogs.png)
![Logs](./images/003-flowlogs.png)

## Egress-Only Internet Gateway

![Egress](./images/004-egressigw.png)
![Egress](./images/005-egressigw.png)

## VPC Endpoints

### VPC Endpoint Gateway

![Endpoints](./images/006-endpoints.png)
![Endpoints](./images/007-endpoints.png)

#### Implementation

### VPC Endpoint Interface

![Endpoints](./images/008-endpoints.png)

???+ tip

    The **Endpoint Interface** uses **privatelink** to connect to the AWS Public services (EXCEPT DynamoDB). You can imagine that the privatelink allow external services to be injected in your VPC and be given network interface inside your VPC subnet.

![Endpoints](./images/009-endpoints.png)
![Endpoints](./images/010-endpoints.png)

#### Implementation



