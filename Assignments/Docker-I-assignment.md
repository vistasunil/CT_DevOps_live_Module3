<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKER COMMANDS </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

#
</br>

## $`\textcolor{red}{\text{NOTE: USE UBUNTU 22.04 VIRTUAL MACHINES FOR ALL THE LABS}}`$

## Scenario

**You work as a Devops Engineer in a leading Software Company. You have been asked to Dockerize the applications on the production server. The company uses custom software, therefore there is no pre-built container which can be used.**

### Exercise 1: Docker Pull and Commit

#### Complete below Exercises to accomplish this: 

**Deploy a container which has apache bundled in docker image**

**Assume the following things:**

* Use an Ubuntu container
* Assume the software to be installed is apache

Execute below tasks to complete this exercise:

* Pull a ubuntu docker image
* Run a container using this ubuntu image
* Login to the container and install apache inside it
* Exit the container
* Save the changes to the container using docker commit

### Exercise 2: Docker Hub and Docker Login, Tag and Push## 

#### Accomplish following things as next action: 

* Create a docker hub account on hub.docker.com.
* Use docker login to login to docker hub account from the server
* Use the new image created in Exercise 1 and tag it to your account name
* Push it to Docker Hub
* Check the image got pushed successfully on Docker Hub by logging into it.

### Exercise 3: Dockerfile

**Download the html website code from below url using wget on the server. Suppose developer has provided you this code in zip file:**

https://www.free-css.com/assets/files/free-css-templates/download/page267/better-clean.zip

**The Developers will not be working with Docker, hence from their side you will just get the code. Write a Dockerfile which could put the code in the custom image that you will build in below steps:**

* Unzip the above html website code you just download
* cd to the unziped folder ## better-clean##  and write a Dockerfile inside this as below:
  * Use the docker image created in Exercise 1 as base image.
  * Copy all the html website code to docker. Code location inside the container should be ## /var/www/html## 
  * Set an environment variable website=better-clean-portal
  * Start the apache process using Entrypoint.
  * Save the file.
* Build this Dockerfile to create a new docker image.
* Now, deploy better-clean website using the above image so that its accessible using public IP of the host (use port mapping)
* Test the website deployed successfully and accessible.
