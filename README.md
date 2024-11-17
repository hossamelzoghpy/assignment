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
