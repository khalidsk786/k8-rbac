# Ingress Controller
    REGION_CODE=us-east-1
    CLUSTER_NAME=expense
    ACC_ID=891377396025
### Permissions
* OIDC Provider
```
  eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
