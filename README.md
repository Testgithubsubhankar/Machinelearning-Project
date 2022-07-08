# Machinelearning-Project
This is first machine learning Project.


Creating conda environment
```
conda create -p subhankar python==3.7 -y
```

```
conda activate subhankar/
```
OR
```
conda activate subhankar
```


```
pip install requirements.txt
```

To add files to git
```
git add
```

OR
```
git add <file_name>
```

Note:To ignore file or folder we can write name of file/folder in .gitignore file

To check the git status 
```
git status
```
To check all version maintained by git
```
git log
```


To create version/commit all changes by git 
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url
```
git remote -v
```

To setup CI/CD pipeline in heroku we need 3 information
1. HEROKU_EMAIL=subhankarmondal1995@yahoo.com
2.HEROKU_API_KEY=e1e0d76e-18c4-42df-b8ce-69507e952a0e
3.HEROKU_APP_NAME=ml1-app

BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname> .
```
> Note: Image name for docker must be lowercase


To list docker image
```
docker images
```

Run docker image
```
docker run -p 5000:5000 -e PORT=5000
```

To check running container in docker 
```
docker ps
```
Tos stop docker container 
```
docker stop <Mcontainer_id>
```
