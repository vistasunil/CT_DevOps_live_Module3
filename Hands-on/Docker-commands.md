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

## Installation:

Refer [Official Docker installation page](https://docs.docker.com/engine/install/ubuntu/) for installation steps.

## Docker Commands

### Step 1: This command helps you know the installed version of the docker software on your system

`docker --version`

![image](https://user-images.githubusercontent.com/37858762/235539910-2b8af734-9840-4adc-b853-a7be12c9eb85.png)

### Step 2: This command helps you pull images from the central docker repository.

`docker pull <image-name>`

![image](https://user-images.githubusercontent.com/37858762/235539951-2e1db83f-f3b6-4bac-b8b2-30309305ac63.png)

### Step 3: This command helps you in listing all the docker images, downloaded on your system.

`docker images`

![image](https://user-images.githubusercontent.com/37858762/235539980-d3cce23b-b6e1-4bb2-a892-7731139495c7.png)

### Step 4: This command helps in running containers, from their image name.

`docker run <image-name>`

![image](https://user-images.githubusercontent.com/37858762/235540001-3d07ab13-d1f1-4730-8277-5c1ed9a19192.png)

### Step 5: This command helps in listing all the containers which are running in the system

`docker ps`

![image](https://user-images.githubusercontent.com/37858762/235540019-d9587944-282f-4431-8c58-c24aa8f2d548.png)

### Step 6: If there are any stopped containers, they can be seen by adding the "-a" flag in this command

`docker ps -a`

![image](https://user-images.githubusercontent.com/37858762/235540037-0ae759f6-07b8-4474-9e78-20276dedfe18.png)

### Step 7: For login into/accessing the container, one can use the exec command

`docker exec <container-id>`

![image](https://user-images.githubusercontent.com/37858762/235540055-b7fc47b8-7ab5-434a-a298-8df89811aefb.png)

### Step 8: For stopping a running container, we use the "stop" command

`docker stop <container-id>`

![image](https://user-images.githubusercontent.com/37858762/235540083-c0dd2446-32fb-484b-aac4-54ad3c460c52.png)

### Step 9: This command kills the container by stopping its execution immediately. The difference between 'docker kill' and 'docker stop'. 'docker stop' gives the container time to shutdown gracefully, in situations when it is taking too much time for getting the container to stop, one can opt to kill it

`docker kill <container-id>`

![image](https://user-images.githubusercontent.com/37858762/235540101-7ef07d6f-c48d-4690-999a-7f03aa81272d.png)

### Step 10: To remove a stopped container from the system, we use the "rm" command

`docker rm <container-id>`

![image](https://user-images.githubusercontent.com/37858762/235540133-b1883405-bdbc-4cd1-93fe-cfb52f1b34a0.png)

### Step 11: To remove an image from the system we use the command "rmi"

`docker rmi <image-id>`

![image](https://user-images.githubusercontent.com/37858762/235540142-9f09a6d3-4694-4af4-9cfa-68c3cfa3d94b.png)
