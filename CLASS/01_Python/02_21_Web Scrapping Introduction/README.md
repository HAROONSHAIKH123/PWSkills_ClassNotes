# AWS DEPLOYEMENT STEPS

```
go to AWS management consoleand login
search beanstalk and select
click create new environment
Web server environment

Then goto elastic beanstalk 
click on creat application
give application name "haroon_review_scrap"
choose platform python
choose plateform branch
Run creat application

search codepipline
select Creat pipeline
give pipeline name "review_scrap"
click next
give source provider - select github version1
select connect to github and conncect
give reposetary name
select branch
select next
skip buildprovider select skip build stage
select deploye provider "AWS elastic beanstalk"
select application name "haroon_review_scrap"
select environment name "as given"
click next
Review all if ok select creat pipeline
```