# Test-Connection

```bash
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 53
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 88
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 389
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 636
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 445
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 5985
Test-NetConnection -ComputerName "DC-AD-NC-HEAD02" -Port 5986

Test-NetConnection -ComputerName "file-services-ap-northeast-1-prod.sentinelone.net" -Port 443
Test-NetConnection -ComputerName "ap-northeast-1-prod-auto-deploy.s3.ap-northeast-1.amazonaws.com" -Port 443
Test-NetConnection -ComputerName "mgmt-file-upload-eu-central-1-prod.sentinelone.net" -Port 443
Test-NetConnection -ComputerName "eu-central-1-prod-auto-deploy.s3.eu-central-1.amazonaws.com" -Port 443
Test-NetConnection -ComputerName "mgmt-file-upload-us-east-1-prod.sentinelone.net" -Port 443
Test-NetConnection -ComputerName "us-east-1-prod-auto-deploy.s3.us-east-1.amazonaws.com" -Port 443
```
