FROM gitlab/gitlab-runner:latest

RUN apt update
RUN apt install sudo -y
RUN adduser gitlab-runner sudo
# RUN mkdir /home/gitlab-runner
# RUN mkdir /home/publish
RUN chmod -R 777 /home/gitlab-runner
RUN echo "gitlab-runner ALL=NOPASSWD: ALL" > /etc/sudoers.d/gitlab-runner
