# RepData_PeerAssessment2
DS5 Reproducible Research Peer Assn 2

### This repo has the following files of the assignment

1. .RMD file --- *ds05report02.Rmd*
2. .MD file ---- *ds05report02.md*
3. .HTML file -- *ds05report02.html*
4. Rpubs link is -- *



#### Notes of remote add
1. git init
2. git remote add origin https://github.com/jderik/RepData_PeerAssessment2.git
3. git pull origin master
4. git add .
5. git commit -m "20150426"
6. git fetch origin master
7. git pull origin master
6. git push master origin

#### Notes for modifying property files to enable publisghing
##### THis is needed as otherwise you get the error 
Error in function (type, msg, asError = TRUE) : 
SSL certificate problem: unable to get local issuer certificate
Calls: rpubsUpload ... <Anonymous> -> .postForm -> .Call -> <Anonymous> -> fun
Execution halted

1. Goto -- C:\Program Files\R\R-3.1.2\library\base\R
2. Copy Rprofile to desktop
3. add this line in Rprofile -- *options(rpubs.upload.method = "internal")*
4. copy Rprofile back to C:\Program Files\R\R-3.1.2\library\base\R
