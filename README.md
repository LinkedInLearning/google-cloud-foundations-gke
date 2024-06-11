# Google Cloud Foundations: Google Kubernetes Engine (GKE)
This is the repository for the LinkedIn Learning course Google Cloud Foundations: Google Kubernetes Engine (GKE). The full course is available from [LinkedIn Learning][lil-course-url].

![lil-thumbnail-url]

This course is designed to provide a solid foundation of knowledge in deploying and managing containerized applications on Google Kubernetes Engine (GKE). Instructor Krishna Gadiraju covers key topics such as Kubernetes fundamentals, GKE cluster architecture, different deployment modes (Autopilot and Standard), as well as practical skills like installing kubectl, configuring cluster access, deploying applications, and configuring monitoring/logging—all aimed to empower you with the knowledge and hands-on experience needed to navigate the complexities of GKE confidently and efficiently.
 
Learn the key GKE components, master deployment strategies, and gain proficiency in essential GKE operations for effective application management in cloud-native environments.

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

### Instructor

Krishna Gadhiraju

AWS & GCP Architect | DevSecOps Expert | YouTuber
                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/krishna-gadhiraju?u=104).


[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/google-cloud-foundations-google-kubernetes-engine-gke
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQE0uQtO5NORZw/learning-public-crop_675_1200/0/1717608714474?e=2147483647&v=beta&t=JskBmvWM8afv_T8FvttCcnBucs2KGPw8fyW4PYv65ag

