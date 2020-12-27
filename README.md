# aws-delete-default-vpc-python

Script to remove default VPCs in every region of the AWS account.

## Usage
```
$ cd ~/environment/aws-delete-default-vpc-python
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $ venv/bin/pip install boto3
(venv) $ deactivate # To deactivate
$ python main.py
```

## References
- Source code copied from https://github.com/davidobrien1985/delete-aws-default-vpc
