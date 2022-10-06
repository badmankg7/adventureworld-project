# adventureworld-project
An explanation of your app and how it fulfils the brief.
my intention was to have a app that would have a database with two relationships related to one another. 
these two relationships would be related by character and class of a character.
i attempted to have the database implemented but struggled with this so instead i built a standard flask application 
which would enable me to be able to later integrate the database for my web spp.

A technical description of how the application works.
although the intention of this application was originally to be able to provide a option for crud functionality 
for a dnd character with related field of clas, i was unsuccessful. so instead a new flask file of code for hello work was deployed. 
the expectation would of been that a user would of been able to access the website to add, change or get information from the database 
to potentially access or display the information already inslucded in the container. from the beginning my script is invoked and also 
the test file with the environment rules are implemented before the build starts. i reserched several pages and found that jenkins was very tempermental
when it came down to adding cregentials for mysqlcontainer. 

A technical description of how the pipeline works.
the pipelinie workes in four different stages. first stage is to outsource through scm script. once this happens second stage starts to build from the code. 
then tests are done to check there are no issues and you are left with the fourth stage which is the result. 

A report on the success and code coverage of your unit tests.
i found that i was struggling with the unit test until i had produced A basic line of code in my jenkins file that enabled it to 
successfully deploy. obviously with the jenkins file it is important to apply different stages like build and test in order for the code to wotk 
right. 

Any future improvements you would make.
i want to be able to successfully link mysql container to the build so that this can alsl be tested. this would require another code 
to be applied to the app.py in order to start the container and possibly to link it as well. i would also be looking to improve the database 
details on the file so that would display on the website with more time. i tried unsuccessfully to add the docker swarm but this would also be 
an improvement. 

included in this github repository will be a video just deplaying the successful implemtnation of the build on pipelines. 

https://drive.google.com/file/d/11zoIKrrA6xGsES1jPF4Oe2rk7sUL0n65/view?usp=sharing
