# techconceptsweb.github.io



Load balancers in GKE can broadly be categorized as internal and external load balancers. Internal refers to the VPC network which is an internal private network not directly accessible from the internet. External refers to the public internet. Note that ClusterIP Services are internal to a single GKE cluster so they are scoped to an even smaller network than the VPC network.

4 Client network.jpg
*Public GKE clusters provide public and private IPs to each GKE node and so NodePort Services can be accessible internally and externally.
