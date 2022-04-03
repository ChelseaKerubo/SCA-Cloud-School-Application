# SCA-Cloud-School-Application

Instructions for Deployment :

1. Once you have created a repository, clone the repository to your PC and write your application.
2. Set up your local directory with the code, commit the main branch with a ReadMe file and  create a branch called Start by **git branch Start** then **git checkout Start** to get into that specific branch.
3. Set up your feature branch by using **git branch feature** then **git checkout feature**  to get into that specific branch
4. Push the code in the feature branch to github : **git push origin feature**
5. Build an image using **docker build -t chelseak/sca_cloud_school** as to be able to run the image on localhost.
6.Run th eapplication using **** docker run chelseak/sca_cloud_school****
7. To push the application onto docker hub use **docker push chelseak/sca_cloud_school**
8.
Docker Hub respository : **https://hub.docker.com/repository/docker/chelseak/sca_cloud_school**
