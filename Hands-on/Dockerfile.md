<div align="center">
<img src=https://static.wixstatic.com/media/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png/v1/fit/w_2500,h_1330,al_c/1c706c_a5df0ad56f894928bf858a74ba744b32~mv2.png width="400" height="200">
 </div>

# <div align="center"> DOCKERFILE </p>

# <div align="center"> DevOps Instructor-led Training </div>

# <div align="right"> $`\textcolor{brown}{\text{Contact us: }}`$  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; </div>

<div align="right"> T O A C C E L E R A T E Y O U R C A R E E R G R O W T H </div>

### <div align="right"> For questions and more details: </div>

<div align="right"> <img src=https://w7.pngwing.com/pngs/759/922/png-transparent-telephone-logo-iphone-telephone-call-smartphone-phone-electronics-text-trademark-thumbnail.png width="20" height="20"> +91 98712 72900 </div>

<div align="right"> <img src=https://pbs.twimg.com/profile_images/1450734615946219520/jmBHQRRa_400x400.jpg width="20" height="20"> https://www.thecloudtrain.com </div>

<div align="right"> <img src=https://icons.iconarchive.com/icons/martz90/circle/512/email-icon.png width="20" height="20"> support@thecloudtrain.com </div>

<div align="right"> <img src=https://png.pngtree.com/png-vector/20221018/ourmid/pngtree-whatsapp-icon-png-image_6315990.png width="20" height="20"> +91 98712 72900 </div>

## CREATING A DOCKERFILE

### Step 1: First, create a folder docker, in the home directory

`mkdir docker`

`cd docker`

![image](https://user-images.githubusercontent.com/37858762/235542195-a0434257-561d-4e2c-a187-398c5ef1e0e7.png)

### Step 2: Enter into this directory, and create a file called 'Dockerfile', with the same contents as the Sample Dockerfile. Add the following content in the Dockerfile.

`sudo vim Dockerfile`

```
FROM ubuntu
ENV TZ=Asia/Kolkata
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
RUN apt-get update
RUN apt-get -y install apache2
ADD . /var/www/html
ENTRYPOINT apachectl -D FOREGROUND
ENV name Devops Tutorial
```

![image](https://user-images.githubusercontent.com/37858762/235542220-2d61e7c2-1362-4d69-8fc9-87c6f8c964ff.png)

`sudo vim index.html`

### Step 3: Create one more file called, index.html with the following contents can verify the push on DockerHub.

![Shape14](RackMultipart20230501-1-8ract0_html_6a2255611f2ba091.gif) ![Shape13](RackMultipart20230501-1-8ract0_html_e7f3579da92fe195.gif)

```
<html>
	<title> Sample Website </title>
	<body>
		Hello World
	</body>
</html>
```

![image](https://user-images.githubusercontent.com/37858762/235542245-e6237b73-d40d-4c9a-a207-59c587a221ee.png)

`docker build <directory-of-dockerfile> -t <name of image>`

![image](https://user-images.githubusercontent.com/37858762/235542265-87c5ca08-780a-40c3-8f43-d055bf692f97.png)

![image](https://user-images.githubusercontent.com/37858762/235542275-5a5f32a6-e684-44da-9747-75ad095e5858.png)

### Step 5: Finally, run this built image, using the following command:

`docker run –it –p 81:80 –d <name of image>`

![image](https://user-images.githubusercontent.com/37858762/235542286-538d598a-624f-491c-af18-61b0a5283774.png)

### Step 6: Now navigate to the server IP address on port 81

![image](https://user-images.githubusercontent.com/37858762/235542299-56141e74-7479-4c0b-9736-cd09cd2a31cc.png)

### Step 7: Finally, login into the container, and check the variable $name, it will have the same value, as given in the Dockerfile.

![image](https://user-images.githubusercontent.com/37858762/235542309-f55b9231-fe50-4cc7-b4d8-01bf0673fa1d.png)
