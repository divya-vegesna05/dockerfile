ARG version
FROM almalinux:$version
ARG username
RUN adduser $username
ARG Training
ARG Trainer
ENV training=$Training
ENV trainer=$Trainer
RUN echo $username $version
USER $username
CMD ["sleep","100"]