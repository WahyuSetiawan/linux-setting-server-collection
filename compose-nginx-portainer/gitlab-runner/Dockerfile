FROM gitlab/gitlab-runner:latest

RUN apt update
RUN apt install sudo -y
RUN adduser gitlab-runner sudo
RUN echo "gitlab-runner ALL=NOPASSWD: ALL" > /etc/sudoers.d/gitlab-runner
