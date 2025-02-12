✨ _**Update (Oct 26, 2023):**_
We are on Hugging Face, get your own SDK Servers by duplicating spaces at https://huggingface.co/FaceOnLive.

✨ _**Update (Apr 10, 2023):**_
Our API portal is now live, offering free APIs for various AI solutions, including face recognition, liveness detection, and ID document recognition.<br/>
Make sure to check it out at https://getapi.faceonlive.com and take advantage of our free offerings.
<h1 align="center">Face Liveness Detection SDK For Linux</h1>
<p align="center">Fully Offline, On-Premise Face Liveness Detection SDK for Linux</p>

<p align="center">
<a target="_blank" href="mailto:contact@faceonlive.com"><img src="https://img.shields.io/badge/email-contact@faceonlive.com-blue.svg?logo=gmail " alt="www.faceonlive.com"></a>&emsp;
<a target="_blank" href="https://t.me/faceonlive"><img src="https://img.shields.io/badge/telegram-@faceonlive-blue.svg?logo=telegram " alt="www.faceonlive.com"></a>&emsp;
<a target="_blank" href="https://wa.me/+17074043606"><img src="https://img.shields.io/badge/whatsapp-faceonlive-blue.svg?logo=whatsapp " alt="www.faceonlive.com"></a>&emsp;
<a target="_blank" href="skype:demidemi1125?chat"><img src="https://img.shields.io/badge/skype-demidemi1125-blue.svg?logo=skype " alt="www.faceonlive.com"></a>
</p>

</br>

### Documentation at https://docs.faceonlive.com
</br>

## :tada:  Try It Yourself on our Portfolio Website
### https://portfolio.faceonlive.com/#server_sdks/server/liv

## :muscle:  Partnership / Cooperation / Project Discussion
&emsp;<a href="mailto:contact@faceonlive.com?subject=[GitHub]%20Face%20Liveness%20Detection%20SDK%20Linux"><img src="https://img.shields.io/badge/mail-%23DD0031.svg?&style=flat&logo=gmail&logoColor=white"  height="64"/></a>
</br>
</br>

https://user-images.githubusercontent.com/91896009/187945910-4ca6d27c-d058-4749-a834-44914a5a957c.mp4


## :clap:  Supporters
[![Stargazers repo roster for @faceonlive/Face-Liveness-Detection-SDK-Linux](https://reporoster.com/stars/faceonlive/Face-Liveness-Detection-SDK-Linux)](https://github.com/faceonlive/Face-Liveness-Detection-SDK-Linux/stargazers)
[![Forkers repo roster for @faceonlive/Face-Liveness-Detection-SDK-Linux](https://reporoster.com/forks/faceonlive/Face-Liveness-Detection-SDK-Linux)](https://github.com/faceonlive/Face-Liveness-Detection-SDK-Linux/network/members)
<p align="center"><a href="https://github.com/nastyox/Rando.js#nastyox"><img src="http://randojs.com/images/barsSmallTransparentBackground.gif" alt="Animated footer bars" width="100%"/></a></p>

## 🏃  How to run
### 1. Download and install dependencies
To begin, follow these steps to download and install the necessary dependencies:
```
git clone https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux
cd Face-Liveness-Detection-SDK-Linux
chmod +x ./install_dependency.sh
sudo ./install_dependency.sh
```
### 2. Execute the Python Flask application
Next, run the Python Flask application by executing the following command:
```
python3 app.py
```
### 3. Activate the SDK
#### - Online License
If you have an online license, please update the license key provided by us in the following file:
https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux/blob/6e702fa01aeabbfb395d82c637a66dc18a93f2fb/app.py#L23-L23
#### - Offline License
If you have an offline license, please share your machine's HWID (Hardware ID) with us to receive the license.txt file. Update the HWID in the following file:
https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux/blob/6e702fa01aeabbfb395d82c637a66dc18a93f2fb/app.py#L24-L24
```
online init failed: 6
hwid:  IXwjedMe8M5cZX/GwU3NEOqJRcqLwldq27HSLyFiejbGDB9XVgytA1RgJukV3mWWTNo84NwTMYU=
```
### 4. Using Docker
- Build the Docker image:
```
sudo docker build --pull --rm -f Dockerfile -t faceonlive_v7:latest .
```
- Run Docker with online license:
```
sudo docker docker run --network host faceonlive_v7
```
- Run Docker with offline license:
```
sudo docker run -v license.txt:/root/FaceOnLive_v7/license.txt --network host faceonlive_v7
```
### 5. Test endpoint
To test the endpoint, download the Postman Collection from the following link:
[FaceOnLive.postman_collection.json](https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux/blob/main/FaceOnLive.postman_collection.json)

![image](https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux/assets/91896009/417e4fe3-9a01-43b3-a95b-d379ad4bdf17)

![image](https://github.com/FaceOnLive/Face-Liveness-Detection-SDK-Linux/assets/91896009/2275503e-49f0-4c72-9922-6e750a26dd62)

