# Task-1 
- Create your github account 
- configure git with your new account 
- create a new repo on your github account 
- clone this repo to your machine 
- create a new branch called feature_a
- make some changes on the branch 
- push the branch to the remote repo
- create a PR to merge your branch to the master branch and add me as a reviewer to approve the changes before merging.

# Answer:
- by using commands of git we can push our changes from our local repo to github by using this command [git push origin feeatue_a]
- but you need first connect to github by ssh by [git clone (your ssh link)]
- and adding your changes to stage area by [git add .]
- and commit this changes by [ git commit -m "Your message" ]
 ![image](https://github.com/user-attachments/assets/f9f0c3fa-94ba-4b6d-aa83-03c1628f90fb)
***********************************************************************************************************************************************
# Task-2
- Run an Nginx Container and make it accessible through your browser.
- then enter the container and restart the Nginx service

# Answer
- by using container commands we can create images and multiple containers from one image in this example, which needs to use ngnix image, create container from it and make some process on it
- first we using this command to run conatiner [ docker run -d --publiush 80:80 --name (name of container) nginx ]
- you can use your browser to check the running status by adding localhost in url browser like under image.
 ![nginx running](https://github.com/user-attachments/assets/18189d81-806a-42b7-88ba-e8246d113dec)
- from under the image you can use this command to restart the nginx 
 ![restart nginx](https://github.com/user-attachments/assets/d3e8cd2a-3abc-492d-bc50-79a8cd192920)
***************************************************************************************************************************************************
# Task-3
- Creating your image using vscode
- then build it
- then take acopy from image and adding it to your dockerhub repo

# Answer
- by using vscode and this command under photo i create my own image
 ![vscode](https://github.com/user-attachments/assets/9fc2b96c-1559-47c1-9e86-3b6f19b1c654)
- then i build this file by using command (docker build --tag my_redis .)
- then i run the container to see action by (docker run --name my_redis_cont my_redis)
- then i take a copy from my image by(docker tag my_redis hossamelzoghpy/my_redis)
- then i push this image to my repo in dockerhub
- you can find this image in this link (https://hub.docker.com/r/hossamelzoghpy/radis)
*****************************************************************************************************************************************************
# Task-4
- Dockerize a Angular App and push your image to Dockerhub

# Answer
- by using vscode and this command under photo i create my own image
 ![angular](https://github.com/user-attachments/assets/587b81fb-ace1-4a00-97f2-825ee1c799a6)

- then i build this file by using command (docker build --tag my_angular .)
- then i run the container to see results by (docker run --name my_angular_cont my_angular)
- then i take a copy from my image by(docker tag my_angular hossamelzoghpy/my_angular:1.0)
- then i login in my dockerhub
- then i push this image to my repo in dockerhub by (docker push hossamelzoghpy/my_angular:1.0)
- you can find this image in this link (https://hub.docker.com/r/hossamelzoghpy/my_angular)
