ARG=0.1.0-alfa.9;\
 git flow release start $ARG &&\
 git flow release finish &&\
 git push origin master develop v$ARG develop:release/$ARG
