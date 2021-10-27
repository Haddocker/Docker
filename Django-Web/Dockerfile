FROM centos:8

#Install nginx
RUN dnf update -y
RUN dnf upgrade -y
RUN dnf install vim -y \
#epel-release \
#nginx \
python3 \
python3-pip
#RUN systemctl enable nginx
RUN pip3 install Django

#EXPOSE 80

#CMD [ "nginx", "-g", "daemon off;" ]


#RUN mkdir /home/scripts/
#WORKDIR /home/scripts/.
    #RUN django-admin startproject mysite

#WORKDIR /home/scripts/mysite/.
    #RUN python3 manage.py runserver
    #RUN python3 manage.py startapp polls
    #RUN vim /home/scripts/mysite/polls/views.py
