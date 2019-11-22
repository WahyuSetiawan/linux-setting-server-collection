FROM gitlab/gitlab-runner:latest

RUN apt update
RUN apt install sudo -y
RUN adduser gitlab-runner sudo
RUN mkdir /home/gitlab-runner; exit 0;
RUN mkdir /home/publish; exit 0;
RUN chmod -R 777 /home/gitlab-runner
RUN echo "gitlab-runner ALL=NOPASSWD: ALL" > /etc/sudoers.d/gitlab-runner
