![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

## CloudFormation Overview

AWS CloudFormation lets you model, provision, and manage AWS and third-party resources by treating infrastructure as code.

## Important Consideration 
In this example, we demonstrate how to create a AWS Redshift stack.  
You will need to make one change to this template. You will need to supply your public IP address under the RSIngress1 rule.  
Set the CidrIp: to your public IP address.  
```YAML
RSIngress1:  
    Type: 'AWS::EC2::SecurityGroupIngress'  
    DependsOn: RSSecurityGroup  
    Properties:  
      CidrIp: 000.00.000.000/32
```

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟