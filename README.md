ARG=0.1.0-alfa.8;\
 git flow release start $ARG &&\
 git flow release finish &&\
 git push origin master develop v$ARG
