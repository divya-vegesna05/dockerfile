ARG version
FROM almalinux:$version
ARG username
RUN adduser $username
ARG Training
ARG Trainer
ENV training=$Training
ENV trainer=$Trainer
USER $username
CMD ["sleep","100"]