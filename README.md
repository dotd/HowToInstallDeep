# HowToInstallDeep

## Amazon instance - ready from carnd
[Follow the Udacity instructions to launch an EC2 GPU instance with the udacity-carnd AMI.](https://classroom.udacity.com/nanodegrees/nd013/parts/fbf77062-5703-404e-b60c-95b78b2f3f9e/modules/6df7ae49-c61c-4bb2-a23e-6527e69209ec/lessons/614d4728-0fad-4c9d-a6c3-23227aef8f66/concepts/f6fccba8-0009-4d05-9356-fae428b6efb4)

1. Visit the EC2 Management Console: [https://console.aws.amazon.com/ec2/v2/home](https://console.aws.amazon.com/ec2/v2/home)
1. Click on the “Launch Instance” button.
1. Search for the “udacity-carnd” AMI (in Community AMIs)
1. Filter the instance list to only show “GPU instances”.
1. Select the g2.2xlarge instance type
1. Finally, click on the “Review and Launch” button
1. Click on the “Review and Launch” button again
1. ssh as `carnd` to the instance, where the password you know.
```
ssh carnd@ec2-34-253-222-144.eu-west-1.compute.amazonaws.com
```

## Install cmake and other things for gym
1. update the apt-get
```
sudo apt-get update
```
2. Install everything we need (cmake, swig, etc.)
```
sudo apt-get install -y python-numpy python-dev cmake zlib1g-dev libjpeg-dev xvfb libav-tools xorg-dev python-opengl libboost-all-dev libsdl2-dev swig
```
## Install Gym
```
pip install gym[all]
```




## Amazon instance
The tutorial is taken from [https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/docker_for_aws.md](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/docker_for_aws.md)

## Anaconda
This is taken from [Udacity - https://github.com/udacity/CarND-Term1-Starter-Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)
and [https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md)
```

```
